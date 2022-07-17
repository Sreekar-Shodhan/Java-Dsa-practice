# Conditional and Loops

- In small programs we execute the statements once but in complex programs we need to execute statements multiple times. For this control flow statements are helpful to execute them easier.

- These loops allow to repeat a set of instructions for many times.

- Conditional statements is an expression that produces a true or false result. These allow us to check the condition and execute certain parts of code depending on whether the condition is true or false.

## If .. If.. else.... If...else..if :

- if a specified condition is true then execute the statement inside the if block, if false then leave.

         if(condition){
            block of code executes if condition is true
        }

- if a specified condition is met then execute the statement within the if block, if not then execute the statement in the else block.

        if(condition){
            block of code executes if condition is true.
        }else{
            block of code executes if condition is false.
        }


- if there are multiple conditions to be checked after first condition is false then we use if.. elseif....else

        if(condition){
            if condition true then execute this
        }elseif(condition){
            if condition true then execute
        }else{
            if condition is false then execute this
        }


## Switch statement

- Switch statement can have a number of possible execution paths. Use switch to specify many alternative blocks of code to be executed.

## Loops 

- There are 3 types of loops. for-loop, while loop, do while loop.

#### for-loop:

- This is a repetition control structure that allows us to write a loop which executes the code specific number of times.

- This is used when we know how many times a task is to be repeated.

        for( i = 0; i < n; i++){
            block of code;
        }
        here i = 0 -> initialization
             i < n -> condition
             i++   -> increment/decrement

#### while loop:

- This executes as long as the loop condition is true. 

- When we need to repeatedly execute a block of statements. It is aslo called as repeating if statement.

- IF the number of iterations are not fixed, then use while loop.

- This is entry controlled loop.

         while(condition){
             execute this block of code untill condition is true
          }

#### do-while loop:

- This is almost similar to while loop but the only difference is the code block will be executed once irrespective of true/false and then the condition is checked.

- IF the number of iterations is not fixed/predictable and must have to execute the loop at least once, it isrecommended to use a do-while loop.

- This is exit control loop.

       do{
        execute this
       }while(condition)


## Differences between while and do-while loops

   | While loop       | Do while loop|
   |-----------       | -------------|
   |Condition is checked first then statements are executed|Statements is executed atelast once, there after condition is checked|
   |IF condition is false then statements execution = 0 times | At least once statement is executed irrespective of true/false|
   |No  semi colon at the end of while| Semicolon at the end of while|
   |If there is a single statement, brackets are not required|Brackets are always required|
   | variable in condition is initialized before execution of loop| variable may be initialized within or before the loop|
   |Entry controlled loop| Exit controlled loop|    



