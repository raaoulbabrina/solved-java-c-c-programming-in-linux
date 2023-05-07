Download Link: https://assignmentchef.com/product/solved-java-c-c-programming-in-linux
<br>
5/5 - (10 votes)

1. This program is intended to get you acquainted with Linux (or refresh your programming experience).  This will be a short interactive program that will get you started an editor in Linux (pico, vi, emacs, etc.).

2. It will get you through compiling, linking, and running a program.  You may write the program in Java, C, or C++ – your choice.

Editing: Program in Linux, use the editors in the Linux environment . There are a number of ways this can be done. The easiest way is to use the pico editor.  Also available are vi and emacs editors.

Compiling: The compiler is gcc  (or g++ or javac). This can be used from the command prompt. Sample compilation is

For C program: gcc –o test test.c                   (source program is test.c)

For C++ program: g++ -o test test.cpp          (source program is test.cpp)

For Java program: javac test.java                 (source program is test.java. This command generates test.class)

Executing: Here, test is the executable file name, and the execution is as follows.

For C or C++ program: . /test

For Java program: java test

Program Description:

Write a small Linux program that will calculate the average of the following five grades:  77, 85, 80, 94, and 97.  The program does not have to accept these grades, they may be hard coded into the program.

You must compute the average as a separate function such as average(sum, numGrades).

Your program should print out the average, and then terminate.

Program requirements:

Enough documentation (either embedded in the code with comments, or external) to explain how you parsed the program and to follow what you expect to happen.

Source code for your program (file name linuxfc.c or linuxfc.cpp or linuxfc.java )