# Intro-To-Java

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
-----------------------

Java has eight fundamental data types, including four integral types: byte, short, int, and long. These types differ in the amount of memory they occupy, which determines the range of values they can represent. For example, byte uses 8 bits of memory and can store values up to 256, while long utilizes 64 bits and can handle numbers as large as 9.2 quintillion.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/88f2c9b5-845a-4830-9b87-12c745a626ef)
- Primitive data types

Moving on to decimal data types in Java, we have float and double. Float provides seven decimal digits, while double offers greater precision with 16 decimal digits. The boolean type simplifies things by representing true or false, akin to one and zero. Lastly, char is used for single characters and should be enclosed in single quotes, distinguishing it from strings.

### Local Variable Type Inference
-------------------------------- 

In Java, although it is statically typed, it supports type inference for local variables. This feature enables you to declare a variable using the keyword VAR, allowing Java to determine the data type based on the assigned value. See the following example for illustration.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/eb90aa49-3932-4237-b243-8f33c7a96037)
- Variable type inference

When declaring a variable like `isWaterWet`, you can choose to use `VAR` instead of `boolean`. However, with `VAR`, you must initialize the variable immediately upon declaration. This type inference only applies to local variables within methods, not global variables at the class level.

### Naming Variables
-------------------

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/ba8fbfa5-2879-4661-b7da-6f20c0f212a0)
- Creating variables

In the GrossPayCalculator program, descriptive variable names like 'hours' and 'payRate' are used to clearly indicate their purpose. While some programmers might use shortcuts like 'h' and 'r', this is not recommended as it can lead to confusion both for others and oneself. Therefore, it is essential to use descriptive names for variables, methods, classes, and packages. This practice is particularly important when collaborating, as it ensures that others can easily understand and update the code.

In Java, variable names can include numbers, special characters like $ or _, but avoid dashes and reserved words. The first character should not be a number. If you accidentally use an invalid name, the compiler will alert you.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/c2322acd-1c1a-4c4f-9323-0e71122387d1)
- Variable naming rules in Java

### Modifying Variables
----------------------

The original GrossPayCalculator program uses fixed values for hours and pay rate, resulting in the same output each time it runs. To enhance the program's flexibility, we can initialize the hours and payRate variables to default values of zero and then prompt the user to input their own values. This allows the program to accommodate different user inputs.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/51416079-ec83-4038-92c2-a0f0a6212ad3)
- Hard coded variables

To read user input in Java, we use a Scanner object. We declare it as `Scanner scanner = new Scanner(System.in)`, which imports the Scanner class from the java.util package. The scanner object allows us to read user input and store it in variables like hours and payRate. After using the scanner, we close it to prevent memory leaks.

![image](https://github.com/MihlaliKota/Intro-To-Java/assets/133135575/039dfc72-988e-44eb-8fbc-2ed915f8a79b)
- Dynamic Variables

The program worked with different numbers for hours and pay rate. You could enter anything, like 30 hours and 8.25 US dollars per hour. 

### Arithmetic Operators
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


