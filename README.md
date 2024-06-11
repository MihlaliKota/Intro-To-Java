# Module 1: Java 101 - Introduction to Java

## Introduction

### What is Java?
----------------

Java is commonly used by newcomers in programming to interact with computers. Software engineers use Java to develop a variety of applications like web, mobile, and desktop apps. These programs require the Java Runtime Environment (JRE) to run, and for creating and compiling Java programs, the Java Development Kit (JDK) is essential, which includes the JRE and necessary tools.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/e6a7af45-a60e-43ab-9ca7-a3be36bce67d)
- Writing and running Java programs

### Algorithms in Programming
----------------------------

Computers are present in various aspects of our lives but require specific instructions (programs) to function. While early programs were written in binary code, programmers have created programming languages like Java to simplify the process. These languages are converted into binary code that the computer can understand. Algorithms, which provide step-by-step guides for computers to follow, are essential for solving problems using programming languages.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/28deafb7-0a49-47d8-a35e-1bb531af0576)
- Various programming languages

To give you an example, think about figuring out how much money an employee makes before deductions. We can create a step-by-step approach for this. Start by finding out how many hours they have worked and then check their hourly wage rate. Next, you multiply those hours by their rate and show the answer. Once you have got this down, you can use a programming language like Java to make it work in real life.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/0a30a99a-cbef-4ef8-acca-e9ed8b9f3111)
- Employee gross pay algorithm

## Getting Your Java Environment Ready

### Getting Your Java Environment Ready - Installing JDK
--------------------------------------------------------

To prepare for developing and running Java applications on our computer, we need to install the Java Development Kit (JDK). This kit includes the Java Runtime Environment (JRE), enabling us to both build and execute Java applications.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/1f83197a-84bd-4e07-b2c4-5df69f84d41c)
- Java JDK Download - https://www.oracle.com/java/technologies/downloads/

The Java Development Kit (JDK) comes in different editions, with 'SE' representing the Standard Edition, which is suitable for our purposes. At the time of writing, the latest version is Java 17.0.2. However, if newer versions are available when you are taking the course, you can use those instead. As you progress in your Java learning, the differences between versions may become more significant. When downloading the JDK, make sure to select the appropriate version for your operating system.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/75c1cd3d-141b-4c77-8f59-02055befb5c9)
- Java JDK Installation

### Installing IntelliJ IDEA
----------------------------

We will utilize IntelliJ, a free and open-source code editor available for download from jetbrains.com/idea. Simply click the download button on the website, and IntelliJ will attempt to detect your operating system automatically. Ensure the correct operating system is identified, select the Community Edition for download, and initiate the download process. After the download completes, double-click to open IntelliJ.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/f3f61692-4e97-4153-a0bc-ea58d69f1908)
- Installing IntelliJ Idea IDE

For Mac users, drag the IntelliJ application into the Applications folder after downloading. Windows users should follow the standard installation prompts. Once the installation is complete, double-click the IntelliJ application icon to launch it. This IDE (Integrated Development Environment) will serve as our primary coding platform moving forward. All our Java code will be written and executed within IntelliJ, making the process straightforward.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/dedd0449-76a6-4eeb-a538-ae69fe75afba)
- Installing IntelliJ Idea IDE

### Executing Java Programs
---------------------------

There are two main approaches to writing and running Java programs:

1. Using a text editor and command line: You can write code in a text editor like Sublime or Atom and then use the command line to compile and execute it. For example, you could create a program that displays "Hello" in the console and run it through the command line.

2. Using an IDE (Integrated Development Environment): As programs become more complex, managing files, changes, rebuilding, and recompiling can become cumbersome and time-consuming when using a text editor and command line. An IDE provides a more efficient solution by offering a comprehensive environment for writing, testing, and running Java code.

Using an IDE offers several key advantages over the text editor and command line approach:

1. IDEs are specifically designed for coding and include built-in tools that streamline the software development process.
2. IDEs provide a graphical user interface (GUI), allowing you to compile and run code with a simple click of a button, eliminating the need for command line typing.
3. IDEs include a debugger, which is invaluable for identifying and resolving errors in your program.

Just as specialized software like Photoshop is preferred for photo editing, IDEs are the go-to choice for editing and running code, making the process quicker and more efficient.

Among the various IDEs available for Java application development, we will be using IntelliJ, created by JetBrains. IntelliJ is specifically designed for Java development and comes in two versions:

1. A paid Ultimate version
2. A free Community version

For this course, the free Community version of IntelliJ will suffice.

### Explore IntelliJ IDEA
-------------------------

For beginners, it is recommended to keep things simple and use a single IntelliJ project for learning the basics. This approach allows us to focus on understanding the fundamentals without the complexity of managing multiple projects.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/1db8a629-e8fc-42a3-a4ae-9b2e21dbd623)
- Starting up IntelliJ

To begin, you will need to create a new project in IntelliJ. This involves configuring several settings, including selecting the version of Java to use for coding and running your programs. For this course, we will use Java 20. Ensure that you have downloaded the JDK for Java 20 before selecting it as the project configuration.

Next, we will name our project "Learning Java" and create a new folder for it on our desktop. Once these steps are complete, we can proceed to create our project by clicking the "Create" button.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9a9d1637-2041-4a18-80c8-775bb76a4a3f)
- Setting up a project in Intellij

Now that IntelliJ is set up, let's explore its features to use it efficiently. The navigation pane on the left is crucial for navigating project files. It includes important folders like `.idea`, which contains project metadata, and `SRC`, which is the main hub for our Java code. This is where we will do most of our coding, making it the "beating heart" of our project.

Additionally, we need to link the JDK (Java Development Kit) in the external libraries section, which is essential for our Java projects.

In the top-right corner, we have buttons for running and debugging our program. For now, we can simply hit the play button to compile and run the program.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/87f6b9e6-427e-445f-8c5e-628ce7c2fc41)
- Setting up a project in Intellij

The run button is currently grayed out because we have not written any Java code yet. To enable the button and run our program, we need to create a Java program first. Let's dive in and start writing some Java code! Exciting times are ahead as we begin our Java programming journey.

### Writing Your First Java Program
-----------------------------------

We are now ready to write our first Java program. To begin, we will create a new Java file in the SRC folder. We have two options to do this: either hover over "New" and create a new Java class called "Hello World" or go to "File" and select "New" > "Java class" to achieve the same result.

Java is known for its verbosity, which means it requires more words to write a simple program. While this can be a drawback for some, it is beneficial for beginners as it helps to clarify concepts and keep the code organized. Every Java program must include a class, which serves as the foundation for all Java code. This is why our file already includes the "public class Hello World" code snippet.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/d3eade6f-3ad9-41fc-b448-cfcccb26265a)
- Writing your first Java program

Now, let's get to the exciting part of writing our first Java program. In computer science, when learning a new language or technology, the traditional first step is to create a program that prints "Hello World." That is exactly what we will do today. To write the code, we will use the code editor in the main pane. If you accidentally close the file, don't worry; you can easily reopen it by double-clicking it in the SRC folder.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/4534f427-414e-4740-a7ff-370d90fa504a)
- HelloWorld program

To modify the code, we are adding extra Java code within the curly brackets. Inside these brackets, we find the `main` function, which serves as the starting point for the program. Any code written within these brackets will be executed when we hit the run button. Up until this point, we have covered the basics of Java programming, but now we can add our own unique touches.

Our program can be customized by what we add within these curly brackets. For example, we can modify the "Hello World" program to print "Hello World, it is me, Kathryn." To achieve this, we use the `System.out.println` method, which is the Java way to output text. We simply place the desired text within the parentheses, such as "Hello World, it is me, Kathryn."

You might be wondering about the "public" keyword in Java, but don't worry; we will explore this concept further in future chapters. For now, we will focus on understanding `void` and `static` in the context of Java programming.

### Running Your First Java Program
-----------------------------------

We have our code, and we want to make some changes. We can easily add more Java code within the curly brackets.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/7de3d54f-5563-43eb-8ad4-d5af612c1405)
- Running your first Java program

The `main` function is the central hub of our program, where everything gets executed when we run the program. So far, we have covered the basic elements that every Java program needs to get started.

The `HelloWorld` class plays the main role, and `main` is the supporting function. When we click the "Run HelloWorld.main" button in the IDE, it's like magic Our program runs without needing manual commands.

After running the program, we see a console window at the bottom of the screen, where the program shares its inner workings. It greets us with a "Hello World!" message, just like Yoda saying hi.

Now, here's the exciting part: we can simplify the running process. After the initial run, we can find a shortcut to a one-click performance in the top-right corner. We can edit this configuration to make it easier to run our program.

Once we've made the changes, the Play button turns green. Clicking it runs our program again, and the console outputs the familiar "Hello World!" message. Congratulations, we've successfully run our first Java program using our IDE.

## Java Essentials

### Java Essentials - Packages
------------------------------

In Java, a package is a folder or container that holds related Java files. To create a package, you first need to set up a project. In IntelliJ, follow these steps:

1. Select "New Project"
2. Choose Java
3. Click "Next"
4. Do not choose a template
5. Name the project "Fundamental"
6. Click "Finish"

This will create a new Java project named "Fundamental" in IntelliJ.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/4224681f-6396-407c-bbe4-5516c4d2cc0f)
- Creating a Java package

In the project view on the left side, we can see the source folder, which is currently empty since this is a brand new project. To create a new package under the source folder, we can right-click, hover over "New," and select "Package."

Packages in Java are like special folders that hold one or more Java files. It's a good idea to organize your code into multiple packages, depending on how it's structured. Packages help group related Java files together.

When prompted to name the package, let's follow the convention and call it "gross_calculator" since it will house the files for this part of the course. After hitting Enter or clicking "OK," you'll see the new "gross_calculator" package in the source folder, indicated by a circular icon.

### Classes
-----------

To create a new class, right-click on the package, select "New," and then choose "Java Class." Java class names typically start with an uppercase letter. For our gross pay algorithm, we name the class "GrossPayCalculator." Since Java does not allow spaces in class names, we use a three-word name without spaces. Each word starts with an uppercase letter, following Java conventions. After naming the class, press Enter to create the new class within the package.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/adaac2fa-fb2e-484e-b8a8-9f36da16c550)
- Creating Java Classes

In Java, packages contain Java files, which are also called classes. To create a new class, you can right-click on the package and select the option to create a new Java class.

The open tab displays the name of the class as "GrossPayCalculator.java." It's important to note that all Java files have a ".java" extension, which indicates that they are Java source code files.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/95804e4b-5d6c-458d-b565-efcfe2a221dc)
- Creating a Java classes file

To make the tab larger, double-click it in the editor. The first line of the Java file is the package declaration. If a Java file belongs to a package (like ours), the first line should declare the package name followed by a semicolon (;). The declaration consists of the word "package" followed by the exact name of the chosen package.

After the package declaration, you'll find the class declaration. Every Java file contains a Java class. This class is declared as a public class named "GrossPayCalculator," enclosed in curly braces. In Java, curly braces group sections of code together. Congratulations! We have created our first Java class. 🎉

### Main Method
---------------

When you see curly braces in Java, remember that any code placed between them is part of the Java class. These curly braces are like code containers, and inside one of them, we will create a method, which is another code container. To make your code run in a Java class, it must be nested inside a method.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/1e839e06-320a-4941-bddf-d4f8b015522c)
- Creating a Java method

To create a method, you would write "public static void main" followed by curly braces. This method is called the "main method" and is where a Java program starts running. When you run the class, Java looks for this main method and begins execution from there. The method must be exactly as specified, with the curly braces and all.

Methods always include curly braces, and everything inside them belongs to that specific method. To see the method in action, we should insert a print statement. In Java, we use "System.out.println" followed by what we want to display within parentheses. A common beginner task is to print "Hello World," so let's do that. We will write "Hello World" inside quotes and end the line with a semicolon.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9f9657c5-8219-4f30-9828-26eba29c118a)
- Writing and running a Java print statement

This line is an instruction that tells Java to display text on the console, and the semicolon marks the end of the instruction. Our class now has a main method with one instruction. To run it for the first time, right-click anywhere in the program and select the 'run' option. You will see a console window open and print 'Hello World' as we instructed. Congratulations, you have created your first Java program.

### Reserved Words
------------------

When examining the code, notice the different-colored words. The specific colors may vary depending on your editor and theme, but in this context, we are referring to words like "package," "public," "class," "static," and "void." These are known as keywords in Java.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/03923158-702b-4189-807a-0eeb6e29743a)
- Java reserved words

In programming, certain words are reserved and have specific meanings defined by the language. These reserved words cannot be used as variable or element names in our program. For example, we cannot name something "class," "public," or "package" because these words are reserved by Java for specific purposes.

There is a long list of reserved words in Java. As we continue to work together, pay attention to the colors in your code. When you type something and it changes color to indicate a reserved word, remember that you have encountered another special term.

## Java Variables

### Creating Variables
----------------------

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

### Primitive Data Types
------------------------

Java has eight fundamental data types, including four integral types: byte, short, int, and long. These types differ in the amount of memory they occupy, which determines the range of values they can represent. For example, byte uses 8 bits of memory and can store values up to 256, while long utilizes 64 bits and can handle numbers as large as 9.2 quintillion.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/88f2c9b5-845a-4830-9b87-12c745a626ef)
- Primitive data types

Moving on to decimal data types in Java, we have float and double. Float provides seven decimal digits, while double offers greater precision with 16 decimal digits. The boolean type simplifies things by representing true or false, akin to one and zero. Lastly, char is used for single characters and should be enclosed in single quotes, distinguishing it from strings.

### Local Variable Type Inference
---------------------------------

In Java, although it is statically typed, it supports type inference for local variables. This feature enables you to declare a variable using the keyword VAR, allowing Java to determine the data type based on the assigned value. See the following example for illustration.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/eb90aa49-3932-4237-b243-8f33c7a96037)
- Variable type inference

When declaring a variable like `isWaterWet`, you can choose to use `VAR` instead of `boolean`. However, with `VAR`, you must initialize the variable immediately upon declaration. This type inference only applies to local variables within methods, not global variables at the class level.

### Naming Variables
--------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/ba8fbfa5-2879-4661-b7da-6f20c0f212a0)
- Creating variables

In the GrossPayCalculator program, descriptive variable names like 'hours' and 'payRate' are used to clearly indicate their purpose. While some programmers might use shortcuts like 'h' and 'r', this is not recommended as it can lead to confusion both for others and oneself. Therefore, it is essential to use descriptive names for variables, methods, classes, and packages. This practice is particularly important when collaborating, as it ensures that others can easily understand and update the code.

In Java, variable names can include numbers, special characters like $ or _, but avoid dashes and reserved words. The first character should not be a number. If you accidentally use an invalid name, the compiler will alert you.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c2322acd-1c1a-4c4f-9323-0e71122387d1)
- Variable naming rules in Java

### Modifying Variables
-----------------------

The original GrossPayCalculator program uses fixed values for hours and pay rate, resulting in the same output each time it runs. To enhance the program's flexibility, we can initialize the hours and payRate variables to default values of zero and then prompt the user to input their own values. This allows the program to accommodate different user inputs.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/51416079-ec83-4038-92c2-a0f0a6212ad3)
- Hard coded variables

To read user input in Java, we use a Scanner object. We declare it as `Scanner scanner = new Scanner(System.in)`, which imports the Scanner class from the java.util package. The scanner object allows us to read user input and store it in variables like hours and payRate. After using the scanner, we close it to prevent memory leaks.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/039dfc72-988e-44eb-8fbc-2ed915f8a79b)
- Dynamic Variables

The program worked with different numbers for hours and pay rate. You could enter anything, like 30 hours and 8.25 US dollars per hour. 

### Arithmetic Operators
------------------------

Java has five operators for basic math calculations. They work with numeric values, such as bytes, shorts, ints, longs, floats, and doubles. 

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/58a310ed-52b6-4fa6-a98c-5359f1880ce6)
- Arithmetic Operators

In Java, the basic arithmetic operators include:

- The plus sign (+) for addition, which can also concatenate strings.
- The minus sign (-) for subtraction.
- The asterisk sign (*) for multiplication.
- The slash sign (/) for division.
- The percent sign (%) for the modulo operation, which returns the remainder of a division operation. For instance, 5 modulo 2 equals 1 because 5 divided by 2 leaves a remainder of 1.

## Decision Structures in Java 

### If Statements
-----------------

In computer programming, decision-making is a crucial aspect, and it's achieved through the use of decision structures, with the "if statement" being the most widely used. This statement enables programs to follow different execution paths based on specific conditions.

To illustrate this concept, let's consider a scenario involving a team of salespeople who earn a base salary of $1,000 per week. However, if a salesperson exceeds 10 sales in a given week, they receive an additional bonus of $250. Typically, the program would pay the salesperson their standard wage of $1,000. However, it needs to evaluate whether the salesperson has made more than 10 sales. If that condition is met, the program adds the $250 bonus to their payment, thereby increasing their overall compensation for that week.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/12f90beb-384a-437d-b814-6b383259d378)
- If statements

The provided code utilizes an If statement to determine whether an employee qualifies for a bonus based on their sales performance. The If statement evaluates if the number of sales made by the employee exceeds a predefined quota. If the sales count surpasses the quota, the employee receives a bonus of $250 in addition to their regular compensation. However, if the sales count does not exceed the quota, the employee does not receive any bonus.

To thoroughly test and comprehend the code's execution, you can run it in debug mode, which allows you to step through the code line by line. For instance, if you run the code with 10 sales, the If statement will not execute because 10 is not greater than the quota. Consequently, the employee's salary will remain at $1,000. Conversely, if you run the code with 15 sales, the If statement will execute because 15 exceeds the quota. In this case, the employee's salary will be $1,250, which includes the base salary and the $250 bonus.

### If-else statements
----------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/72a100e8-33c3-48f7-9930-28cfb3e4706f)
- If-else statement

The if-else statement is a decision-making construct in programming that enables a program to follow one of two distinct paths based on whether a specific condition is satisfied or not. It serves as a conditional branching mechanism that allows the program to execute different blocks of code depending on the evaluation of the provided condition.

To illustrate, consider a scenario where a program needs to determine if a salesperson has achieved their sales quota. In this case, the program could utilize an if-else statement. If the salesperson has indeed met their quota, the program would execute a block of code that prints a congratulatory message, acknowledging their accomplishment. However, if the salesperson has not met the quota, the program would instead execute an alternative block of code that prints a message encouraging them to put in more effort during the next sales period.

The if-else statement provides a structured way for programs to make decisions and execute different actions based on the fulfillment or violation of specific conditions, thereby introducing control flow and branching logic into the program's execution.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/f1edda53-8d62-4cce-baa9-c308b590d9fb)
- If-else statements in QuotaChecker

The provided code is designed to evaluate whether a user has met a predefined sales quota and provide feedback accordingly. The code begins by initializing the quota to 10 sales. It then prompts the user to input the number of sales they made during the current week. Subsequently, the code employs an if-statement to assess if the user's sales count is greater than or equal to the quota.

If the user's sales meet or exceed the quota, the code will print a message informing them that they have successfully met their quota. Conversely, if the user's sales fall short of the quota, the code will execute the else branch, printing a message that indicates the user did not meet the quota and specifying the number of sales they were deficient by.

The code achieves this by utilizing the salesShort variable, which stores the difference between the quota and the user's actual sales count when the quota is not met. This value is then incorporated into the message displayed to the user, providing them with specific feedback on the number of sales they need to make up.

Overall, this code demonstrates the implementation of conditional branching using an if-else statement, allowing the program to follow two distinct execution paths based on whether the user's sales performance meets the predetermined quota or not. It exemplifies how programming languages provide control structures to handle alternative scenarios within a single code block.

### If-Else-If Statements
-------------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/5dd14c1e-4287-41e5-8eef-b6f067f0c1fc)
- If-Else-If statement

The if-else-if statement is a versatile tool that can be used to control the flow of a program. It can be used to execute different code blocks based on multiple conditions, which can be helpful for things like grading tests, determining eligibility for discounts, or making other decisions.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/b7b5b647-b693-484b-822f-b6160989da52)
- If-Else-If decision structure

The provided code aims to determine a student's grade based on their numerical score. The grading system consists of five possible grades: A, B, C, D, and F. To assign the appropriate grade, the code employs an if-else-if decision structure, which allows it to cover all five potential grade outcomes.

Initially, the code declares a character variable called `grade` to store the final grade value. Since the value of the grade is unknown at this point, the if-else-if decision structure is used to evaluate the score and determine the corresponding grade.

The process begins with an if statement that checks if the score is less than 60. If this condition is true, the `grade` variable is updated to 'F'. If the condition is false, the code moves on to the next condition.

The next condition checks if the score is less than 70. If this condition is true, the `grade` variable is assigned the value 'D'. If the condition is false, the code proceeds to the subsequent condition.

The third condition evaluates whether the score is less than 80. If this condition holds, the `grade` variable is set to 'C'. If the condition is false, the code continues to the following condition.

The fourth condition checks if the score is less than 90. If this condition is true, the `grade` variable is assigned the value 'B'. If the condition is false, the code moves to the final else block.

In the final else block, if none of the previous conditions were met, the `grade` variable is assigned the value 'A'. This condition is satisfied when the score is greater than or equal to 90.

By employing this if-else-if decision structure, the code ensures that all possible grade outcomes are covered, and the appropriate grade is assigned based on the provided score. This approach demonstrates how programming languages provide control structures to handle multiple conditions and execute different code paths based on the evaluation of those conditions.

### Switch Statements
---------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c57f696c-ee88-4589-9b46-aa40c8fc9d7a)
- Switch statements

The switch statement is a control flow structure in programming that operates similarly to the if-else-if decision structure, but it is particularly well-suited for situations involving multiple options or cases. The key difference between the switch statement and the if-else-if structure lies in the way they evaluate conditions. While the if-else-if structure checks for various logical conditions, the switch statement specifically checks for equality against a given value or expression.

To illustrate the use of the switch statement, consider a scenario where a user inputs their grade as a letter (e.g., A, B, C, D, or F). The switch statement can be employed to display a corresponding message based on the user's input grade. The program would evaluate the provided letter grade against multiple cases within the switch statement, and when a matching case is found, the associated code block would execute, displaying the appropriate message.

The switch statement simplifies the coding process when dealing with multiple cases or options, as it provides a more concise and readable syntax compared to using multiple nested if-else statements. Instead of checking for various conditions, the switch statement directly compares the input value against predefined cases, making it efficient and easier to maintain, especially when dealing with a large number of potential cases.

In summary, the switch statement is a powerful control flow structure that excels in scenarios where there are multiple options or cases to be evaluated based on the equality of a value or expression. It offers a more concise and readable alternative to the if-else-if structure, particularly when dealing with a large number of potential cases, enhancing code readability and maintainability.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/4d862747-f81e-4de1-9bb0-2f9b89dd9310)
- Switch statements decision structures

The code has a variable called "grade" that stores the user's letter grade input. There's another variable called "message" that needs to be assigned a corresponding message based on the grade value. This is where the switch statement comes into play.

The switch statement starts with the keyword "switch" followed by parentheses containing the expression to be evaluated, in this case, the "grade" variable. Inside the curly braces, multiple cases are defined.

Each case represents a possible value of the "grade" variable. For example, case 'A': would handle the situation when the grade is 'A'. After the colon, you can specify the code to be executed for that particular case, such as setting the "message" variable to "Excellent job".

It's important to include a "break" statement after each case's code block. This ensures that the program exits the switch statement after executing the code for the matching case, preventing it from executing the code for the subsequent cases.

The switch statement allows you to cover all valid grade values by defining a case for each letter grade (e.g., 'A', 'B', 'C', 'D', 'F'). If the user inputs an unexpected value that doesn't match any of the defined cases, the "default" case is executed, acting as a catch-all for invalid inputs.

It's crucial to remember that only one case will be executed – the first one that matches the evaluated expression. If a "break" statement is omitted, the program will continue executing the code for the subsequent cases until it encounters a "break" or reaches the end of the switch statement, leading to unintended behavior.

While the if-else-if structure is suitable for a variety of conditions, the switch statement can be more concise and readable when dealing with multiple cases based on equality checks against a single expression or variable.

The explanation emphasizes the importance of choosing the appropriate control flow structure (if-else-if or switch) based on the specific requirements of the task at hand.

### Switch Expressions
----------------------

Switch expressions provide a more concise and convenient way to assign values based on various cases, particularly when assigning values to variables.

Instead of declaring a separate variable and then assigning its value using a switch statement, switch expressions allow you to combine these steps into a single expression. This is achieved by placing an equal sign (=) after the variable name and moving the switch structure to the right side of the assignment.

Additionally, switch expressions utilize an arrow (->) notation instead of the colon (:) followed by the assignment, making the case statements more concise and readable. The arrow notation represents the assignment operation for the corresponding case.

For example, if you have a variable called "message" that needs to be assigned a value based on a letter grade, you can use a switch expression like this:

```
message = switch (grade) {
    case 'A' -> "Excellent job";
    case 'B' -> "Well done";
    // ... other cases
    default -> "Invalid grade";
};
```

In this example, the value assigned to the "message" variable is determined by the switch expression, which evaluates the "grade" variable against the defined cases. If the grade is 'A', the "message" variable is assigned the value "Excellent job". If it's 'B', the value "Well done" is assigned, and so on.

The use of switch expressions streamlines the code by combining the variable declaration, value assignment, and case evaluation into a single expression. This approach can make the code more concise, readable, and easier to maintain, especially when dealing with multiple cases and variable assignments.

In summary, switch expressions are an enhanced version of switch statements that allow for more compact and convenient variable assignments based on various cases, utilizing an arrow notation for assignment within each case.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9ef8371e-8bd3-4608-adad-8150e59ca9e8)
- Switch expressions

Additional advantages and use cases of switch expressions compared to traditional switch statements. Here's a summary:

1. No need for break statements: One of the benefits of switch expressions is that they don't require break statements like switch statements do. This eliminates the need to include break statements after each case, making the code more concise and reducing the risk of accidental fallthrough errors.

2. Semicolon after closing curly brace: Switch expressions have a more streamlined look, as they require a semicolon after the closing curly brace, making the overall syntax cleaner.

3. Handling multiple cases with the same code: Switch expressions allow you to list multiple cases separated by commas, making it easier to handle situations where the same code needs to be executed for multiple cases. For example, if you want to assign the same message for both 'A' and 'B' grades, you can list case 'A', case 'B': "Excellent work".

4. Including more than just assignments: While switch expressions are particularly useful for assigning values, they are not limited to that. You can include more complex code within each case by enclosing the statements in curly braces after the arrow. This allows for greater flexibility and more intricate logic within each case.

The explanation also provides guidance on when to choose between switch statements and switch expressions. If the primary goal is to assign a value based on different cases, switch expressions are an excellent choice due to their concise syntax and the ability to handle assignments seamlessly. However, if the requirement is to simply execute different statements based on different cases without assigning values, traditional switch statements might be more suitable.

In summary, switch expressions offer several advantages over switch statements, including the elimination of break statements, a more streamlined syntax, the ability to handle multiple cases with the same code, and the flexibility to include more complex logic within each case. The choice between switch statements and switch expressions should be based on the specific requirements of the task at hand.

### Relational Operators
------------------------

Relational operators are these symbols that you use when you are dealing with conditions. Think of them like decision-making tools in Java. Picture this: Java has these six special operators, and they help us figure out if something's true or false.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/63591cf6-bc9e-4171-8f49-37ba9cf05455)
- Relational Operators

This is a breakdown and explanation of the six relational operators in Java:

1. **Greater Than Operator (`>`):** This operator checks if the value on the left-hand side is greater than the value on the right-hand side. For example, if we compare "Is 2 greater than 3?", the answer would be false.

2. **Less Than Operator (`<`):** This operator does the opposite of the greater than operator. It checks if the value on the left-hand side is less than the value on the right-hand side. For instance, if we ask "Is 2 less than 3?", the answer would be true.

3. **Greater Than or Equal Operator (`>=`):** This operator checks if the value on the left-hand side is either greater than or equal to the value on the right-hand side. For example, the statement "4 is greater than or equal to 4" would be true.

4. **Less Than or Equal Operator (`<=`):** This operator checks if the value on the left-hand side is either less than or equal to the value on the right-hand side. For instance, the statement "4 is not less than or equal to 3" would be false.

5. **Equal To Operator (`==`):** In Java, a single equal sign (`=`) is used for assignment, not for comparison. To check if two values are equal, we use the double equal sign (`==`). For example, if we ask "Is 3 equal to 2?", the answer would be false.

6. **Not Equal To Operator (`!=`):** This operator checks if two values are not equal. It is denoted by an exclamation mark followed by an equal sign (`!=`). For instance, if we ask "Is 3 not equal to 2?", the answer would be true.

These relational operators are commonly used in conditional statements, such as `if` statements, to make decisions based on the truthfulness of the conditions formed by comparing values using these operators.

### Logical Operators
--------------------- 

Logical operators let you mix and match conditions to give you one clear yes or no answer, like a Boolean value. They come in handy when you have tricky requirements for making decisions.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/236d79f5-e33d-4716-b417-766c37a15fa6)
- Logical operators

The explanation provides an overview of the three logical operators in Java: AND (`&&`), OR (`||`), and NOT (`!`). These operators are used to combine or negate conditions in order to make decisions based on multiple criteria.

The example given is about determining if someone qualifies for a loan based on two conditions: earning at least $30,000 and having worked at their current job for at least two years. To evaluate such scenarios with multiple conditions, logical operators come into play.

1. AND Operator (`&&`): This operator is represented by two ampersands (`&&`). It combines two conditions, and for the overall result to be true, both conditions must be true. In the loan example, if the person earns $30,000 or more AND has worked at their job for two years or more, then they qualify for the loan.

2. OR Operator (`||`): This operator is represented by two pipes (`||`). It combines two conditions, and for the overall result to be true, at least one of the conditions must be true. For example, if the loan criteria were "earning $30,000 or more OR having worked at the job for two years or more," the person would qualify if they meet either of those conditions.

3. NOT Operator (`!`): This operator is represented by an exclamation mark (`!`). It negates or flips the truth value of a single condition. If the condition is true, the NOT operator makes it false, and vice versa. For example, if the condition is "NOT earning $30,000 or more," then the person qualifies for the loan if they do not meet the earning criteria.

The explanation highlights that logical operators allow you to combine multiple conditions using AND, OR, or NOT, enabling you to make decisions based on complex criteria. Understanding how these operators work is essential for writing effective conditional statements and control flow structures in Java programs.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/0f0e84e2-c5d0-4c85-ae56-81b07108cf41)
- Logical operators examples

The explanation covers the usage and behavior of the three logical operators in Java: AND (`&&`), OR (`||`), and NOT (`!`), through practical examples.

1. AND Operator (`&&`):
The example demonstrates the AND operator with two conditions: `1 <= 2` and `4 <= 5`. The first condition (`1 <= 2`) is true on its own. However, when using the AND operator, both conditions must be true for the overall expression to be true. The second condition (`4 <= 5`) is also true. Since both conditions are true, the final result of the AND operation is true.

2. OR Operator (`||`):
In this case, the example has two conditions: `3 == 4` and `6 > 1`. The first condition (`3 == 4`) is false, but the second condition (`6 > 1`) is true. With the OR operator, only one of the conditions needs to be true for the overall expression to be true. Since the second condition is true, the final result of the OR operation is true.

3. NOT Operator (`!`):
The example shows the NOT operator with the condition `2 != 3`. This condition (`2 != 3`) is false on its own. However, when the NOT operator is applied, it flips or negates the truth value of the condition. Therefore, the result of applying the NOT operator to the condition `2 != 3` is true.

The explanation effectively illustrates how the logical operators work by using simple conditions and evaluating the truth values of the overall expressions. It highlights that the AND operator requires both conditions to be true, the OR operator requires at least one condition to be true, and the NOT operator negates or flips the truth value of a single condition.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/24ce7714-4c62-47d9-b115-b62eed820291)
- Logical operators examples

Here is a little demo of the AND logical operator in an if-else situation. You have two things to check before someone can get a loan:

First, you see if their salary is at least as high as what is needed for the loan. But just having a good salary is not enough by itself. 
You must also ensure they have worked long enough, like, for the required number of years. 
Only if both of these checks come out as true will they qualify for the loan. These logical operators are pretty handy because they let you keep the code nice and clean, without getting all tangled up in nested if statements.

### Short Circuit Logic
-----------------------

The 'and' and 'or' logical operators help us combine two conditions into one. When we use 'and,' both conditions must be true. If the first condition is false, there is no need to check the second one because both have to be true for the whole thing to be true. So, it speeds things up by not evaluating unnecessary conditions.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c90b8a6f-5219-4945-b6e0-33e355ed3ad0)
- Short circuiting logic

Similarly, with 'or,' if the first condition is true, there is no need to bother with the second condition. This is like a shortcut in logic, where we stop evaluating once we know the final outcome.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/e4ec6f18-b9c3-4d78-b892-deb7fc56b13c)
- Short Circuiting Logic AND example

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/8608d4ad-10de-4983-a054-723b0d0b1f06)
- Short Circuiting Logic OR example

The example provided demonstrates how the logical operators AND (`&&`), OR (`||`), and their evaluation order work in programming. It also showcases the concept of short-circuiting, where the evaluation of subsequent conditions may be skipped if the result can be determined based on the initial conditions. Here's a summary:

1. The example has three conditions combined into one using logical operators.
2. The program evaluates the conditions from left to right.
3. For the first combination, `false && true`, the program immediately returns `false` after evaluating the first condition (`false`) because with the AND operator (`&&`), if one condition is `false`, the entire expression must be `false`, regardless of the other condition(s).
4. In the second combination, `true || false`, the program doesn't bother evaluating the second condition (`false`) because the first condition (`true`) is already `true`, and with the OR operator (`||`), it only requires one `true` condition for the entire expression to be `true`.
5. The result of the first operation (`true`) is then combined with the next condition using the AND operator (`&&`). Since both conditions are `true`, the entire expression becomes `true`, and the program prints "IF".
6. The concept of short-circuiting is highlighted, where the evaluation of subsequent conditions is skipped if the result can be determined based on the initial conditions, saving computational resources.
7. Understanding short-circuiting and the evaluation order of logical operators can help organize conditions more efficiently and potentially optimize code performance.

The explanation effectively conveys how logical operators are evaluated, the concept of short-circuiting, and the importance of understanding these concepts for efficient code organization and potential performance optimizations.

## Repetition Structures in Java

### While Loop
---------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/192f71c8-a8db-4064-9d2a-85d8e84ff004)
- Loops image

Loops are a programming construct that allows code to be executed repeatedly, instead of having to write the same set of instructions multiple times. They provide a way to automate repetitive tasks and avoid redundancy in the code. Here's a summary of the key points:

- Loops help prevent the need to copy and paste the same code over and over again, which can lead to maintainability issues and errors.
- They enable the code to perform a specific task or set of instructions repeatedly, without having to manually write out the same lines of code multiple times.
- Loops continue to execute the code within their block until a certain condition is met or a specific number of iterations is reached.
- By using loops, programmers can write more concise and efficient code, making it easier to maintain and update in the future.
- Loops are a powerful tool that adds automation and efficiency to programming, allowing for the repetition of code execution without manual intervention.

In essence, loops are like a magical spell that enchants the code to perform repeated actions automatically, saving developers time and effort while promoting code quality and maintainability.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/352d36c6-5621-4d7e-b965-132be11479e8)
- While Loop

Let's explore a problem that requires a loop to solve. Imagine you're running a store where each employee earns $15 per hour. You need to create a program that allows you to input the weekly hours worked by each employee and calculates their pay, but there's a condition: no overtime is allowed!

To address this, we'll use a "GrossPayInputValidator" program. The pay rate is $15 per hour, and employees can work a maximum of 40 hours per week without overtime. We'll ask for the weekly hours worked and store this input in the "hoursWorked" variable, then calculate the gross pay.

However, to prevent overtime, we must validate the input. Simply checking if "hoursWorked" is 40 or less isn't enough since users might enter incorrect values multiple times. We need a way to ensure they provide valid input.

Here's the strategy: Place the input validation inside a loop. We'll use a "while" loop with a condition. If the condition is true, the loop executes the code within the curly braces.

What should trigger our loop? If "hoursWorked" exceeds "maxHours," the loop starts. This indicates that the entered hours are too high, so we keep prompting for the correct input. Inside the loop, we display a message like "Invalid entry. Your hours must be between 1 and 40. Try again." Then, we update the "hoursWorked" variable with the new input.

The loop continues until valid data is entered. It rechecks the condition after each iteration, and if "hoursWorked" is still too high, the loop repeats. Once the correct input is provided and the condition is false, the loop ends, and the program proceeds.

To test the program, inputting 56 hours prompts an error message. Entering 43 hours also triggers an error. But entering a value under 40 exits the loop, allowing the program to calculate and display the pay.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/24af9c51-eaf7-4731-9946-aa638656d678)
- While loop factors

The deal with while loops is they roll as long as a certain condition holds true. Before diving into the loop, they check if that condition is still a go, and if not, they do not even bother with the loop. You want to go with a while loop when you have a situation where you might have to keep running some code, but it all depends on whether that condition stays legit.

### Do While Loop
-----------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/601399c2-63ca-445f-8678-eeb35e479e98)
- Do while loop

A "do while" loop is similar to a "while" loop, but with a key difference: it checks the condition after executing the loop's code, ensuring the loop runs at least once. While "do while" loops aren't as commonly used as "while" loops since the latter typically suffice, it's useful to understand how "do while" loops function.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9f486b91-4dc1-4f5b-8f0a-6e38db0e2611)
- Do while loop

In this task, you need to create a program that continuously adds numbers input by the user until they decide to stop. To achieve this, we'll use a "do while" loop, which ensures that the loop runs at least once before checking a condition to determine if it should continue.

Here's the plan: Start with "do" and enclose the loop's actions within curly braces. Inside these braces, include the operations you want the loop to perform. After the braces, add "while" with a condition in parentheses, and don't forget the semicolon to complete it.

The loop's condition will check if the user wants to repeat the process. We'll create a variable called "runAgain" initialized to zero. If "runAgain" equals one, the loop continues. Inside the loop, prompt the user for two numbers, call them "number1" and "number2", then calculate and display their sum.

It's important to update the "runAgain" variable to control the loop. Ask the user if they want to repeat: if they enter "1" for "yes," update "runAgain" to continue; if they enter "2," the loop ends.

When the program starts, it enters the "do while" loop. For example, if the user inputs "2" and "3," the program calculates and displays "5". If they want another round, they can input "1" to continue. If they enter "3" and "4" next, the sum "7" is displayed. Finally, if they enter "2" to stop, the loop ends. This is how the "do while" loop works in this context.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/92ace03e-37f7-4827-8685-203b96e6ceac)
- Do while loop key factors

The "do while" loop is similar to the "while" loop, but with a key difference: it checks the condition after executing the loop's code. This ensures that the loop runs at least once. If you need a loop that must execute its actions at least once before evaluating a condition to decide whether to repeat, the "do while" loop is the right choice.

### For Loop
------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c25d543f-07f5-425d-9e53-3ba30a98b203)
- For loop

The "for" loop is unique because it's driven by counting rather than a condition. It knows in advance how many times to execute. For example, in a program for a cashier, the "for" loop can keep track of the number of items scanned while calculating the total cost. This makes it ideal for scenarios where the number of iterations is predetermined.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/848e1b7e-c41c-4d42-bcb5-71442bc3ac1e)
- For loop

On line 18, we stored the number of items the cashier wants to scan, and on line 20, we set the total price to zero. Now, we set up a "for" loop to sum the prices of each item. To begin, write "for" followed by parentheses containing three statements:

1. The first statement initializes a counter, "i," to track the number of loop iterations, typically starting from zero. If the cashier scans three items, "i" will range from zero to two, covering three iterations.
2. The second statement specifies the condition for the loop to continue: "i" must be less than the number of items. This ensures the loop runs the correct number of times.
3. The third statement updates the counter, incrementing "i" by one using "i++."

Enclose the loop's actions in curly braces. Inside the loop, prompt for the price of each item and add it to the total. After the loop finishes, print the total price outside the loop, as it should only be displayed once. Close the scanner and print the total with a message like "Your total is" followed by the total amount.

To test this, run the program in debug mode, setting a breakpoint inside the loop. When prompted for the number of items, enter four. The loop starts with "i" at zero and asks for the item cost. Entering 20 updates the total to 20 and increments "i" to one. Repeating this process with costs of 30, 10, and 25 updates the total accordingly. The loop exits after the fourth item, and the final total is displayed.


![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9d24051a-9f09-400e-8950-a22ef410210f)
- For loop Key factors

When using "for" loops, remember these key points: they are designed for counting and will run the specified number of times without deviation. They check the condition before each iteration, ensuring precise control. If you need a loop to execute a set number of times, "for" loops are the ideal choice.

### Nested Loops
----------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/eb22ef41-8189-4744-8c3d-152a00eebc1e)
- Nested Loop

When handling tasks that include repetitive sub-tasks, you can use a loop within another loop, known as "nested loops." For instance, to calculate the average test scores for a class of 24 students who took four tests each, you would use nested loops. The outer loop would iterate through each student, and the inner loop would handle the scores of the four tests for each student.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/0f731a34-1ff6-4369-8631-1310d8a7ad25)
- Nested loop

To handle the task of processing test scores for 24 students, we use nested "for" loops. Here's how it works:

1. **Outer Loop (Students):**
   - We start by initializing a variable "i" to zero.
   - The loop continues as long as "i" is less than the total number of students (24).
   - With each iteration, we increment "i" by one, focusing on one student per loop cycle.

2. **Inner Loop (Tests):**
   - For each student, we initialize a new variable "j" to zero for another loop to handle their test scores.
   - This loop runs four times, once for each test.
   - We cannot reuse "i" from the outer loop, so we use "j" to count the tests.

3. **Calculating Scores:**
   - Before entering the inner loop, we initialize a "total" variable to zero to accumulate the test scores.
   - Inside the inner loop, we prompt for and read each test score, adding it to "total".
   - For clarity, we use "j + 1" when displaying the test number since "j" starts at zero.

4. **Calculating Averages:**
   - After exiting the inner loop, we calculate the average score for the student by dividing "total" by the number of tests.
   - We print the average, displaying the student number as "i + 1" for better readability.

5. **Repeat for All Students:**
   - The outer loop continues, repeating the process for all 24 students.

This example illustrates nested "for" loops, but you can nest different types of loops depending on the problem. For instance, you could use nested "while" loops or a "while" loop inside a "for" loop, based on the specific challenge.

### Break Statement
-------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/f9b24069-6b25-4857-acd5-fe4f3af51d2b)
- Break statement

Sometimes, you must break free from a loop, no matter what is going on in there. You can do that with the break statement. Imagine we are making a program to hunt down the letter A in a string.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/bf8e4f07-c076-4a3d-83cb-c68d719f0b5f)
- Break statement

The text input is ready, and now we'll search through it using a "for" loop. We start by initializing a variable "i" at zero and set the loop to run until "i" reaches the end of the text, determined by checking if "i" is less than the text's length. After each iteration, we increment "i" by one.

Inside the loop, we retrieve the current letter using "text.charAt(i)" and store it in the variable "currentLetter." We then check if "currentLetter" is either an uppercase 'A' or a lowercase 'a'. If it is, we set "letterFound" to true and break out of the loop using the "break" keyword, as continuing the loop is unnecessary. The "break" statement is effective in all loop types.

## Methods in Java

### Creating Methods
--------------------

In Java, methods are essential tools within a class that allow us to break down complex problems into smaller, more manageable tasks. They perform specific functions and help avoid code repetition. While other programming languages may refer to them as functions or modules, in Java, we refer to them specifically as methods.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/48ae7fc3-af3f-4962-996d-36ee4612300f)
- Method breakdown

Methods in Java are tools designed to perform specific tasks and provide results. They begin with a header, which acts like an identification card specifying who can access them. If a method is declared "public," it can be used by any part of the program; otherwise, it's restricted to its package.

The header includes additional details such as "static" or "final," although not all methods require these modifiers. Crucially, it also specifies the return type, indicating the type of value the method will produce. For instance, an "int" return type signifies that the method will return a whole number.

Following the method's name in the header are parentheses, which serve as a receptacle for any necessary input the method requires. These parameters can be empty if the method doesn't need external data, but if it does, the specific inputs required are listed inside these parentheses.

Each method has a unique signature, consisting of its name and parameter list, which distinguishes it from other methods within the class. After the header, enclosed in curly braces, lies the body of the method—the actual code that executes when the method is called.

If the method doesn't return "void" (meaning it returns a value), it must conclude with a "return" statement, which sends the computed result back to where the method was called from. In Java, "return" holds a special significance as it finalizes the method's execution by passing back the desired outcome.

### Calling Methods
-------------------

A method remains inactive until prompted to execute. For instance, in a program, we might first define a method to greet users by their names. Subsequently, we activate this method from our main method. It's important to note that all methods reside within a class's scope, and their sequence in the code doesn't significantly affect their functionality.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/fda080c2-5bba-49e8-af6a-331812249257)
- Greeting method

In Java programming, the order in which methods are written within a class doesn't affect their functionality; what matters is the sequence in which you call them. For example, our "greetUser" method could be positioned anywhere in the class, either before or after the main method. Its purpose is straightforward: it prompts the user for their name, stores it, and then uses that name to greet them warmly.

However, simply writing the method isn't enough to make it execute. When you run a Java program, it starts executing from the main method by default. To activate the "greetUser" method, you need to explicitly call it by name within the main method or from any other method, regardless of where it's positioned within the class. This involves typing "greetUser();" to invoke it. Once called, the "greetUser" method will execute and perform its intended task of greeting the user with their name.

### Variable Scope
------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/adabce22-b5ef-4daf-8912-541064744df0)
- Variable Scope

A method does not run unless someone requests it. Imagine we are writing a code that creates a method to say hi to someone by their name, and then we are calling this method from our main code. All these methods have to chill inside a class, but the order you list them in does not really matter.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/e9cd439a-047c-47be-bb67-b162cfe65eda)
- Variable scope illustration

Variables in Java are akin to limited edition stickers—they are confined to where they are declared. If you define a variable within a specific scope enclosed by curly braces, such as "method1," you can only access it within that scope. Attempting to reference the variable in another method like "method2" will result in an error because the variable is confined to its home within "method1" and cannot be used outside of those curly braces.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/a3cd68b3-f78f-48cd-9ed8-5806ca8d3dc4)
- Variable scope illustration

A variable's scope in Java can be more limited than just within a method; it can be confined to a specific block of code, as seen in this example. At line four of the code snippet, a variable named "myVariable" is defined within an "if" statement. The scope of "myVariable" is determined by the curly braces surrounding its declaration. Therefore, "myVariable" can only be utilized within the confines of that particular "if" block. Even though line six is within the same method as "myVariable," it is outside of its scope and cannot refer to it.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/9ddb460d-1359-4f33-af5b-450d24a03ea3)
- Local variable scope illustration

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/2f172508-1003-4b6a-93ac-2bc69c1a651a)
- Global variable scope illustration

Local variables are defined within methods, such as those inside loops or if statements. Conversely, global variables are defined outside of methods, typically within the class's curly braces. Global variables have broader accessibility, spanning the entire class, and can be accessed from any method within that class.

In cases where both a global variable and a local variable share the same name, the local variable takes precedence within its narrower scope. For instance, if "myVariable" is declared globally on line two of a class, it can be accessed throughout the class. When referenced within "method1" on line five, the local variable named "myVariable" doesn't exist within the method, so the global "myVariable" is used by default.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/b05d4c8b-64af-4353-b2fd-7662c2efb95b)
- Variable Scope examples

When programming, variables can have different scopes that affect how they are accessed and used. Local variables are defined within methods, like those inside loops or conditional statements. In contrast, global variables are declared outside of methods, typically within the class's curly braces. Global variables have wider accessibility, being accessible from any method within the class.

If a variable is declared both globally and locally with the same name, the local variable takes precedence within its narrower scope. For example, if "myVariable" is declared globally and then re-declared locally within a method, references to "myVariable" within that method will refer to the local instance.

In another method, if "myVariable" is referenced and there is no local variable of that name, the global variable will be used by default. Modifications to "myVariable" within this context will affect the global variable's value. To explicitly refer to the global variable within a local scope, you can use the keyword "this" followed by the variable name. This informs the compiler that you want to access the version of "myVariable" associated with the class.

When deciding whether to declare a variable globally or locally, consider where it needs to be used in your program. Use a local variable if it's only needed within a specific method or block of code. Opt for a global variable if it needs to be accessed and modified across multiple methods within the class.

### Passing Data to Methods
---------------------------

Methods often require external data to perform their tasks effectively. This external data is provided through parameters, which act as inputs. For instance, consider a situation where we want to determine if someone qualifies for a loan based on their salary and credit score. Initially, in the main method, we collect these details from the user.

To make a decision regarding loan eligibility, we create a separate method called "isUserQualified." This method will be defined outside of the main method and will take parameters such as salary and credit score as inputs. Its purpose is to evaluate these inputs against certain criteria to determine if the user meets the qualifications for a loan.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/7c0a8d54-92d2-43a4-8686-f8b661405771)
- Passing data to methods

The method "isUserQualified" requires access to the user's salary and credit score, which are initially confined within the main method. To enable "isUserQualified" to utilize these variables, we include them as parameters in its parameter list. Each parameter is defined with a specific data type and name, such as "int_creditScore" and "double_salary".

Inside "isUserQualified", we introduce additional variables for the required salary (set at $25,000) and the required credit score (set at 700). An "if" statement is then implemented to evaluate if the user meets these criteria. If they do, an approval message like "Congrats, you have been approved" is printed; otherwise, a message indicating decline, such as "Sorry, you have been declined", is displayed.

Once "isUserQualified" is defined and configured, it needs to be invoked to execute its logic. This invocation occurs directly from the main method by using its name and passing in the credit score and salary as arguments. It's important to note that despite using the same variable names for salary and credit score in both methods, they exist within different scopes, ensuring clarity and preventing confusion for the compiler.

Furthermore, if the variable names in the main method are changed to "actualSalary" and "actualCreditScore", the method call to "isUserQualified" must be updated accordingly. This adjustment ensures there are no errors, as the order in which arguments are passed must align with the parameter list's order in the method definition. This strict adherence maintains clarity and precision for the compiler.

### Returning Data from Methods
-------------------------------

Methods in Java perform actions and can optionally return values. Take the example of the "isUserQualified" method. Currently, it performs checks but doesn't return any value—it's a one-way operation. However, to enhance its functionality to return a yes or no answer (like true for approval and false for rejection), we modify its return type to boolean. 

With this change, when the conditions inside the "if" statement are met, the method returns true; otherwise, it returns false. This allows the method to not only perform evaluations but also provide feedback based on those evaluations by returning a boolean value indicating whether the user qualifies for a loan.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/56ef454e-5fc3-4e00-924d-d29070b2ee02)
- Returning data from methods

When we use a method that returns a value, we capture that value and store it in a variable. Previously, we did this with methods like "nextDouble". This time, we'll do the same with "isUserQualified" and store its result in a variable called "qualified".

Next, consider the method "notifyUser". It requires a boolean value (yes or no) when called, which it uses to determine the appropriate message to display. In the main method, we call "notifyUser" and pass it the "qualified" variable.

During execution, when "isUserQualified" is called, the "qualified" variable receives its answer. If the value is false, "notifyUser" outputs a message like "Sorry, you have been declined". This process resembles following a flowchart, where each step depends on the result of the previous one.

### Overloading Methods
-----------------------   

In Java, method overloading allows you to have multiple methods with the same name but different parameters within the same class. This concept is demonstrated in our "Month" class, where we have two "getMonth" methods. Each method's signature, defined by its name and parameter list, distinguishes it from others. One version of "getMonth" accepts an integer representing the month, while the other version takes a string as the month's name. 

This approach is permissible because Java uses the method's parameter list to determine which version of the method to execute when it is called. You specify which method you intend to use by providing arguments that match the corresponding parameter list. Attempting to define overloaded methods with identical parameter lists results in a compilation error, indicating that the method is already defined. Even small variations in parameter names do not circumvent this rule; the parameter types and order must differ for successful method overloading.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/782367bd-d737-482b-8c28-44d98494f8d3)
- Overloading methods

Method overloading provides a convenient method for creating similar methods with slight variations. It enables cleaner code by allowing different scenarios to be handled with distinct methods, avoiding the clutter of conditional logic within a single method. This approach enhances code readability and maintainability by logically separating functionalities that differ based on parameters.

## Objects in Java

### Defining Classes for Objects
--------------------------------

In programming, objects are like containers that hold both data and actions. By creating an object, you can use these data and actions in various parts of your code. This concept is similar to building a blueprint for a rectangle, which includes all its features.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c959a4b5-b8f9-4e70-9bf2-6654aaa0ed03)
- classes for objects

Think of a rectangle as a tangible object that can be held, with characteristics like length and width. These characteristics are like labels, which we call "fields." We declare these fields as "double length" and "double width."

This class is a blueprint for creating rectangle objects. To create a specific rectangle, you would give it values for length and width later. Currently, the rectangle has no values, so if someone asks for its perimeter, it's like trying to calculate the area of nothing. We need a way to set these values. One way is to create "getter" and "setter" methods. These methods allow you to ask for the length or width with "double get length" or "double get width," and change them with "void set length" and "void set width." This way, anyone who uses a rectangle object can give it the right measurements.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/e45e05d8-5a09-4d45-b56a-208493a007ec)
- Encapsulation

In object-oriented programming (OOP), encapsulation is a fundamental concept that emphasizes keeping a class's data (fields) private while making its methods (behavior) accessible to other classes. To achieve encapsulation, we add a "private" label to our length and width fields and a "public" label to the methods we want to share, such as those for calculations and getters and setters. This ensures that our class is properly encapsulated.

There is another access modifier called "protected," which is like a semi-public VIP area. Only classes within the same package can access it, similar to having no access modifier at all. Our rectangle class is like a blueprint, and encapsulation helps keep its internal workings private while making its methods accessible to other classes.

### Java Constructors
---------------------

In addition to using setter methods, you can also set values for a class's fields using a constructor. Constructors are useful for initializing an object's state or setting its initial values. Every object has a constructor, and the default one is the first one you encounter.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/5e58ed8e-b7b0-4fba-800f-18f83cc9778a)
- Constructors

A default constructor is a constructor that does not take any parameters. If you want to create a rectangle object but are not ready to decide on its length or width yet, you can use this constructor without providing any values. The purpose of a default constructor is to give fields some default values.

In Java, a default constructor is always present, even if not explicitly defined. It is an empty constructor that doesn't do anything.

Let's break down the constructor:
- Constructors start with a keyword like 'public'
- They don't have a return type, even though they act like methods
- The constructor's name must match the class name exactly (in this case, 'Rectangle')
- They may have a set of parentheses containing parameters, but our default constructor has none
- Curly braces enclose the constructor's body

For a default constructor, the goal is to assign default values to the class's fields. In our case, we are setting the length and width to zero.

You can have multiple constructors with the same name as the class but different parameters. For example, let's create another constructor for those who know the length and width upfront. We'll use 'public Rectangle' again but ask for 'double length' and 'double width' as parameters. To set the fields, we'll call the setter methods and pass the received parameters. This provides options for setting up a rectangle's state using these constructors.

### Object Instantiation
------------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/f4f2a0ff-a3bd-47a0-9d1a-b1171bf900d8)
- Object instantiation

To calculate the area of rooms, we will create two objects based on the Rectangle class in the HomeAreaCalculator class. To create an object, we must instantiate the class it is based on. In this case, we are creating a room object that takes cues from the Rectangle class. We specify the object's data type as Rectangle, which is a class, not a basic data type like int or Boolean.

Next, we give the object a name, "room1". We create an instance by using the keyword "new" followed by the class's constructor. Since the Rectangle class has two constructors, we will use the default one with no parameters. We say "Rectangle()" and add a semicolon. This creates the object.

We can access an object's methods using the dot operator. We type the object's name, "room1", followed by a dot. We see a list of methods we can use with this Rectangle object. We set the width using "setWidth" and give it a value of 25, and set the length using "setLength" and give it a value of 50. Now that our room has meaningful dimensions, we can calculate the area using "room1.calculateArea".

We create another room object, "room2", using the constructor that takes the length and width as arguments. We say "Rectangle room2 = new Rectangle" and feed it values. When we parse 30 and 75, IntelliJ assigns the corresponding values to "length" and "width".

Using this constructor is like doing the same thing as lines 11 through 13, but in one line. To calculate the area of this room, we say "double areaOfRoom2" and use our trusty "room2" object to call "calculateArea".

We have used the Rectangle class to model physical rooms. This class, like many others, does not care what you use it for. In our case, it is the blueprint for all kinds of rectangles, and we have chosen to use it to represent rooms in a house, which is a type of rectangle. In summary, a class is like a blueprint you can use to create specific objects tailored to your needs.

### Method Parameters as Objects
--------------------------------

Objects can be used as method arguments, similar to primitive data types. For example, we have two Rectangle objects, representing the kitchen and bathroom, which we created by calling the Rectangle constructor and providing length and width values.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/b3a8638d-571b-4817-ada3-8311ce188955)
- Method parameters as objects

To find the total area, we create a public static method named calculateTotalArea that returns a double and takes two Rectangle objects as input parameters. Inside the method, we use the dot operator to call the calculateArea methods on the two objects and return their sum.

In the main method, we call calculateTotalArea with the kitchen and bathroom objects as arguments. We store the returned value in a variable named totalArea. Finally, we print the total area with a message like "The total area is" followed by the area value.

This demonstrates how to use objects as method parameters, allowing us to perform operations on them and return results.

### Method Return Types
-----------------------

To create a method that returns both the length and width of a rectangle, we need to work around the limitation that methods can only return one value at a time. One way to do this is to make the method return an object, which can hold multiple values. Then, we can access the length and width of that object.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/b435435b-a57d-4737-906c-b6dc17de41bb)
- Method return types

Instead of directly creating kitchen and bathroom objects with fixed dimensions, we will use a method to create them. This method, called getRoom, will ask the user for the length and width and return an object with those dimensions.

We can modify the getRoom method to return a Rectangle object instead of directly creating one. We specify the return type as Rectangle and create a new Rectangle object using the provided length and width. We then return this object.

For the kitchen, we set the length to 200 and the width to 400. For the bathroom, we set the length to 300 and the width to 700. 

### Wrapper Classes
-------------------

Wrapper classes, such as Integer, can transform primitive data types like int into objects. For example, number1 is an int, while number2 is an Integer, which is the objectified version of int. This transformation allows us to use the object's methods, which are not available with primitive data types.

Using wrapper classes like Integer provides additional functionality compared to using primitive data types like int. This is because wrapper classes come with a set of useful methods that can be used to manipulate and work with the data.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c816c054-3da9-4642-998d-73720d933790)
- Wrapper classes

The wrapper classes, such as Integer, are available for all basic data types and offer a range of useful methods. The Integer class, in particular, is like a treasure chest for handling integers. It provides constants like MIN_VALUE and MAX_VALUE to determine the smallest and largest values an integer can hold. Additionally, it includes methods like compare and compareTo for comparing integer values, conversion methods like doubleValue and floatValue to convert integers to other data types, and the parseInt method to convert a string with numbers into an actual integer.

If you need to convert a plain integer variable into an Integer object to use these methods, you can use the valueOf method. Similar methods and features are available in other wrapper classes.

### Records
-----------

A record in Java is similar to a class, but it is designed specifically for simple objects with fields and methods to handle those fields. For example, to create an "account" model, we use the "record" keyword instead of "class". We wrap the fields inside parentheses and curly braces. This creates a record with the specified fields. 

Unlike a regular class, there's no need to write getter or setter methods for the fields. They are automatically generated in the background. However, if you want to add more methods, you can simply include them inside the curly braces.

Records provide a concise way to define simple data structures, reducing the boilerplate code required in a regular class.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/d2fd8c5a-c5e4-4f46-88c9-ac9a35d5fae6)
- Records

Creating records is similar to creating classes. For example, to create an "account" record, you would say "new account" and provide the field values through the constructor.

The key difference is that records are immutable, meaning once the field values are set, they cannot be changed. Unlike classes, records do not have setter methods, but they do have accessor methods. These accessor methods do not follow the conventional "get" naming convention; instead, they use the same name as the field itself. For example, you would access the "balance" field as "account.balance" rather than "account.getBalance".

Records are particularly useful when working with simple objects that are set up once and accessed later in the code. These objects are often referred to as Plain Old Java Objects (POJOs). In summary, records provide a convenient way to simplify the code for basic objects.

# Module 2: Java 102 - Java Fundamentals

## Inheritance

### Inheritance
---------------

Inheritance is a concept in programming where a new class, called the child or subclass, inherits all the attributes and methods from another class, known as the parent or superclass. This allows the child class to build upon the parent class, essentially extending its functionality.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/68b3ab5b-b996-46d3-9782-aa3a083cca0f)
- Inheritance

Inheritance enables classes to reuse and build upon existing data and functionality from other classes. Subclasses, being specialized versions of their parent classes, inherit and extend the capabilities provided by their superclasses.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/a5f4a4e0-6b36-4102-af3f-0dff62bfc0b7)
- Inheritance illustration

Let's demonstrate inheritance with code. 

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/228f960c-69e4-4dd6-8af4-6b98b3cc6ef0)
- Person Class

The concept of inheritance is demonstrated by creating a 'Person' class with attributes like 'name,' 'age,' and 'gender,' along with methods to access and modify these attributes. To create a more specialized 'Employee' class that inherits from 'Person' and adds additional information specific to employees, the 'extends' keyword is used in the 'Employee' class declaration.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/03f60f77-ed50-487a-8089-04c6cf47100a)
- Employee Class

The 'Employee' class inherits attributes and methods from the 'Person' class using the 'extends' keyword. This means 'Employee' automatically receives the 'name,' 'age,' and 'gender' attributes and their corresponding getter and setter methods from 'Person.' 'Employee' can then focus on its own unique attributes, such as 'employeeId' and 'title,' and create getter and setter methods for these using a shortcut. The 'Person' class serves as the superclass, while 'Employee' is the subclass, and the inheritance occurs through the 'extends' keyword in the subclass declaration.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/527565b8-a6aa-4a9f-8dfb-998e9e55c2ee)
- Inheritance Checker

The 'InheritanceChecker' class demonstrates the usage of objects from the 'Person' and 'Employee' classes. When using the dot operator with the 'person' object, you can access the getter and setter methods for 'age,' 'gender,' and 'name' that are defined in the 'Person' class. However, when using the dot operator with the 'employee' object, you can access not only the methods inherited from the 'Person' class but also the methods defined within the 'Employee' class itself.

Inheritance is a fundamental concept in object-oriented programming, allowing for efficient code reuse between related classes. By mastering inheritance, you have successfully grasped a crucial aspect of Java programming, enabling you to effectively share and build upon existing code.
