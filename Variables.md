# Variables

### Types

##### Integer Types

- **char**: It represents a single character and is typically used to store ASCII values. It has a size of 1 byte.
- **short**: It represents short integers. The size of a short is typically 2 bytes.
- **int**: It is used to represent integers. The size of an int varies across different platforms but is typically 4 bytes.
- **long**: It represents long integers. The size of a long can vary but is generally 4 bytes or 8 bytes.

##### Floating-Point Types

- **float**: It is used to store single-precision floating-point numbers. It has a size of 4 bytes and can represent a wide range of values with moderate precision.
- **double**: It is used to store double-precision floating-point numbers. It has a size of 8 bytes and provides a larger range and higher precision than float.

##### Void Types

- **void**: It is a special type that represents the absence of a value. It is commonly used as the return type of functions that do not return any value. Additionally, pointers can be declared with void to indicate a generic pointer that can be typecasted to any other pointer type.

##### Signed Types

By default, most variable types in C are signed, meaning they can represent values from negative to positive. For example, a **char** variable can range from -128 to 127, and an **int** variable can range from -2147483648 to 2147483647. However, using the **unsigned** keyword allows you to represent only non-negative values. For instance, an **unsigned char** variable can range from 0 to 255.

### How To Use Variables

##### Declaration

Before using a variable, it needs to be declared. The declaration specifies the variable's name and its data type, informing the compiler about the type of data the variable will hold. For example:
```
int age;
```

##### Initialization

Initialization assigns an initial value to a variable at the time of declaration. It is optional but recommended to avoid using uninitialized variables. For example:
```
int age = 25;
```

##### Assignation

You can assign values to variables using the assignment operator (=). For example:
```
age = 25;
```

##### Reading and Writing

You can read the value stored in a variable or update its value using assignment statements. For example:
```
int x = 10;
int y = x + 5;  // y will have the value 15
```