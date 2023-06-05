# Functions

### How To Use Functions

##### Declaration

A function declaration specifies the function's name, return type, and parameters (if any). It informs the compiler about the existence and signature of the function. For example:
```
int addNumbers(int a, int b);
```

##### Definition

The function definition provides the actual implementation of the function. It includes the function header (declaration), followed by the function body enclosed in curly braces. For example:
```
int addNumbers(int a, int b) {
    int sum = a + b;
    return sum;
}
```

##### Call

To execute a function, you need to call it by its name and provide the necessary parameters (if any). For example:
```
int result = addNumbers(3, 5);
```