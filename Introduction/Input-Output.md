# Basic Input-Output in Java

There are 3 standard or default streams that java has to provide which are most commonly used.

## 1. System . in:

- This is the standard input stream that is used to read characters from keyboard or any other standard input device.

## 2. System.out:

- This is standard output stream that is used to produce the result of a program on a  output device like computer screen.

## 3. System.err:

- This is the standard error stream that is used to output all the error data that a programmight throw, on a computer screen or any standard output device.


### Java output:

The following are the functions used to output the data:

- System.out.println();

- System.out.print();

- System.out.printf();

- - Here, System -> class
         out -> it accepts output data
         print-> prints the accepted data

#### Difference between println(),print(),printf :

- __print():__ It prints string inside the quotes.

- __println():__ It prints string inside the quotes similar like print() method. Then the cursor moves to the beginning of the next line.

- __printf():__ It provides string formatting similar to printf in C/C++.

## Java input:

Get input from the user by using the object of "Scanner" class.

In order to use the object of scanner,  import java.util.Scanner package.

Then, create an object of Scanner class. Use object to take input from the user.


    import java.util.Scanner;

    Scanner input = new Scanner(System.in);

    int num = input.nextInt();

    System.ot.println("the number entered: " + num);

    close();


- Above we have created an object named input of the Scanner class.

- Next called nextInt() method of the Scanner class to get an integer input from the user.

- close() method to close the object. It is recommended to close the scanner object once the input is taken.


