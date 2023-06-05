# Overview

### Coding

The first step is to write your algorithm using an integrated development environment (IDE) or a text editor. Save the file with a **.c** extension, as it is the standard extension for C source files. Remember that you can have multiple C files in a program, but you should have only one main function.

### Compilation

To compile your program and generate an executable file, you'll use the **gcc** command. This command is commonly used for compiling C programs. The basic usage is:
```
gcc file1.c file2.c -o program.exe
```
In this command, you specify the names of the C files you want to compile (e.g., file1.c and file2.c). The **-o** flag is used to specify the output file name (program.exe in this example). The **gcc** compiler translates your C code into machine-readable instructions that can be executed by the computer.

### Execution

Once you have successfully compiled your program, you can execute it in the terminal or command prompt. If your program accepts command-line arguments, they can be passed at this stage. For example, if you run '**./program.exe hello world**', it will call the main function with '**argc = 3**' (indicating three arguments) and '**argv = {"./program.exe", "hello", "world"}**'. The argc variable represents the number of command-line arguments, and argv is an array of strings containing those arguments.