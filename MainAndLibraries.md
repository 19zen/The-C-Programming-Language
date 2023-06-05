# Main And Libraries

### Main Function and Parameters

##### Introduction

The **main** function is a special function in C that serves as the entry point of a C program. When you run a C program, the execution starts from the **main** function, and it is mandatory for every C program to have a **main** function.

##### Declaration

There is 2 way to write the **main** function:
- without parameters
```
int main(void) {
    ...
}
```
- with parameters
```
int main(int argc, char *argv[]) {
    ...
}
```
Here, **argc** represents the number of command-line arguments passed to the program, and **argv** is an array of strings containing the command-line arguments.

##### Return Value

The **main** function should conclude with a return statement that specifies an integer value. By convention, a return value of 0 indicates successful program execution, while a non-zero value usually signifies an error or abnormal termination. The return value is often used by the operating system to determine the status of the program.

### Standard Libraries

##### Introduction

Standard libraries in C are collections of pre-defined functions and header files that provide a wide range of functionality for common tasks. These libraries are specified by the C language standards, such as the ISO/IEC 9899 standard (commonly referred to as C89, C90, or C99). Standard libraries are supported by most C compilers and are typically available on all platforms.

##### Standard Libraries List

- **<stdio.h>** for input/output operations
- **<stdlib.h>** for memory allocation, conversion, and other general-purpose functions
- **<math.h>** for mathematical functions
- **<string.h>** for string manipulation functions
- **<time.h>** for time and date functions
- **<stdbool.h>** for Boolean values (C99 and later)
- ...

Standard libraries provide a portable and reliable way to perform common tasks in C programming. They follow the language standards and are widely supported across different platforms and compilers. Each library contains a list of functions you can use.

##### Standard Functions List

- **printf**: Print formatted output to the console.
- **fopen**: Open a file.
- **fscanf**: Read formatted input from a file.
- **fclose**: Close a file.
- **strlen**: Get the length of a string.
- **strcpy**: Copy a string.
- **strcmp**: Compare two strings.
- **time**: Get the current time.
- ...

##### How To Use Standard Functions

You can use the keyword **include** to add a standard library to your program. Here is an example of an Hello World program in C.
```
#include <stdio.h>

int main(void) {
    printf("Hello World\n"); // print 'Hello World' to the console
    return 0; // 0 is success
}
```
