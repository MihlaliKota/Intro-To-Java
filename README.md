# Intro-To-Java

## What is Java?
----------------

Java is commonly used by newcomers in programming to interact with computers. Software engineers use Java to develop a variety of applications like web, mobile, and desktop apps. These programs require the Java Runtime Environment (JRE) to run, and for creating and compiling Java programs, the Java Development Kit (JDK) is essential, which includes the JRE and necessary tools.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/e6a7af45-a60e-43ab-9ca7-a3be36bce67d)
- Writing and running Java programs

## Algorithms in Programming
----------------------------

Computers are present in various aspects of our lives but require specific instructions (programs) to function. While early programs were written in binary code, programmers have created programming languages like Java to simplify the process. These languages are converted into binary code that the computer can understand. Algorithms, which provide step-by-step guides for computers to follow, are essential for solving problems using programming languages.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/28deafb7-0a49-47d8-a35e-1bb531af0576)
- Various programming languages

To give you an example, think about figuring out how much money an employee makes before deductions. We can create a step-by-step approach for this. Start by finding out how many hours they have worked and then check their hourly wage rate. Next, you multiply those hours by their rate and show the answer. Once you have got this down, you can use a programming language like Java to make it work in real life.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/0a30a99a-cbef-4ef8-acca-e9ed8b9f3111)
- Employee gross pay algorithm

## Java Variables
-----------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/25c9e719-f743-4a3f-b0b0-26292db32f8c)
- Algorithm to calculate an employee’s gross pay

Let's break it down. We have this algorithm for figuring out how much an employee gets paid, right? Now, in the main method, those steps for the algorithm are all there, but they are just sitting there, all commented out.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/d1af29b1-1c27-4636-9c30-d60d21d1435e)
- Algorithm to calculate an employee’s gross pay

Comments are notes programmers write for themselves, not for the computer, which are indicated by two forward slashes at the start of a line. They are not required for the program to run but act as reminders. Variables are used to store information, but if a variable name appears red on the screen, it indicates an error because the Java compiler does not recognize the variable, as it has not been declared yet.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/78e6263c-284d-4a7f-ae61-a28144c5dc26)
- Dynamically Typed vs Statically Typed Programming Languages

Programming languages come in two formats: dynamic typed and static typed. In dynamic languages like JavaScript, the data type of a variable is figured out as the program runs. No need for upfront type declarations here. But in the world of statically typed languages, like Java, you must declare the variables before using them, because they want to check the data type at compile time.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/36daffcc-7c8d-409c-885d-2e147faba31e)
- Creating Variables

In this example, we have a variable called "hours" that will hold an integer value representing the number of hours worked. To declare it, we use the keyword "int" followed by the variable name and assign it the value 40. Next, we introduce another variable called "pay rate" to store the hourly pay rate, which is a decimal number. Since decimal numbers require more memory, we use the "double" data type to declare this variable and assign it the value 25.50.
To calculate the gross pay, we multiply the "hours" variable by the "pay rate" variable and store the result in a new variable called "gross pay." Since the multiplication of an integer and a decimal can result in a decimal, we declare "gross pay" as a "double" data type. Finally, we print the result using "System.out.println," creating a string that includes the "gross pay" variable.

## Primitive Data Types
-----------------------

Java has eight fundamental data types, including four integral types: byte, short, int, and long. These types differ in the amount of memory they occupy, which determines the range of values they can represent. For example, byte uses 8 bits of memory and can store values up to 256, while long utilizes 64 bits and can handle numbers as large as 9.2 quintillion.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/88f2c9b5-845a-4830-9b87-12c745a626ef)
- Primitive data types

Moving on to decimal data types in Java, we have float and double. Float provides seven decimal digits, while double offers greater precision with 16 decimal digits. The boolean type simplifies things by representing true or false, akin to one and zero. Lastly, char is used for single characters and should be enclosed in single quotes, distinguishing it from strings.

## Local Variable Type Inference
-------------------------------- 

In Java, although it is statically typed, it supports type inference for local variables. This feature enables you to declare a variable using the keyword VAR, allowing Java to determine the data type based on the assigned value. See the following example for illustration.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/eb90aa49-3932-4237-b243-8f33c7a96037)
- Variable type inference

When declaring a variable like `isWaterWet`, you can choose to use `VAR` instead of `boolean`. However, with `VAR`, you must initialize the variable immediately upon declaration. This type inference only applies to local variables within methods, not global variables at the class level.

## Naming Variables
-------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/ba8fbfa5-2879-4661-b7da-6f20c0f212a0)
- Creating variables

In the GrossPayCalculator program, descriptive variable names like 'hours' and 'payRate' are used to clearly indicate their purpose. While some programmers might use shortcuts like 'h' and 'r', this is not recommended as it can lead to confusion both for others and oneself. Therefore, it is essential to use descriptive names for variables, methods, classes, and packages. This practice is particularly important when collaborating, as it ensures that others can easily understand and update the code.

In Java, variable names can include numbers, special characters like $ or _, but avoid dashes and reserved words. The first character should not be a number. If you accidentally use an invalid name, the compiler will alert you.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c2322acd-1c1a-4c4f-9323-0e71122387d1)
- Variable naming rules in Java

## Modifying Variables
----------------------

The original GrossPayCalculator program uses fixed values for hours and pay rate, resulting in the same output each time it runs. To enhance the program's flexibility, we can initialize the hours and payRate variables to default values of zero and then prompt the user to input their own values. This allows the program to accommodate different user inputs.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/51416079-ec83-4038-92c2-a0f0a6212ad3)
- Hard coded variables

To read user input in Java, we use a Scanner object. We declare it as `Scanner scanner = new Scanner(System.in)`, which imports the Scanner class from the java.util package. The scanner object allows us to read user input and store it in variables like hours and payRate. After using the scanner, we close it to prevent memory leaks.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/039dfc72-988e-44eb-8fbc-2ed915f8a79b)
- Dynamic Variables

The program worked with different numbers for hours and pay rate. You could enter anything, like 30 hours and 8.25 US dollars per hour. 

## Arithmetic Operators
-----------------------

Java has five operators for basic math calculations. They work with numeric values, such as bytes, shorts, ints, longs, floats, and doubles. 

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/58a310ed-52b6-4fa6-a98c-5359f1880ce6)
- Arithmetic Operators

In Java, the basic arithmetic operators include:

- The plus sign (+) for addition, which can also concatenate strings.
- The minus sign (-) for subtraction.
- The asterisk sign (*) for multiplication.
- The slash sign (/) for division.
- The percent sign (%) for the modulo operation, which returns the remainder of a division operation. For instance, 5 modulo 2 equals 1 because 5 divided by 2 leaves a remainder of 1.


