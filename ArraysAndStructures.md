# Arrays And Structures

### How To Use Arrays

##### Introduction

In C, an array is a collection of elements of the same data type, stored in contiguous memory locations. Arrays provide a convenient way to store and manipulate multiple values of the same type as a single entity.

##### Declaration

To declare an array, you specify the data type of its elements followed by the array name and the number of elements enclosed in square brackets **[]**.
```
int numbers[5]; // Array of 5 integers
```

##### Initialization

Arrays can be initialized at the time of declaration using an initializer list enclosed in curly braces **{}**. The number of elements in the initializer list determines the size of the array.
```
int numbers[5] = {1, 2, 3, 4, 5}; // Array of 5 integers initialized with specific values
```

##### Indexing

Elements in an array are accessed using indices, starting from 0 for the first element. You can access individual elements by using the array name followed by the index in square brackets.
```
numbers[0] = 10; // Assigning a value to the first element
int x = numbers[2]; // Accessing the third element and assigning it to a variable
```

##### Multidimensional Arrays

C supports multidimensional arrays, allowing you to create arrays with more than one dimension. They can be thought of as arrays of arrays.
```
int matrix[3][3]; // 2D array of integers
matrix[0][0] = 1; // Assigning a value to an element in a 2D array
```

### How To Use Structures

##### Introduction

In C, a structure is a composite data type that allows you to group together variables of different types under a single name. It enables you to create a custom data type that can hold related data items, making it easier to organize and manipulate complex data structures.

##### Declaration

To define a structure, you use the **struct** keyword followed by the structure's name. Inside the structure, you list the member variables (also called fields or members) along with their data types.
```
typedef struct {
    char  name[50];
    int   age;
    float height;
} Person;
```

##### Initialization

You can initialize a structure at the time of declaration using curly braces **{}**.
```
Person person_1 = {"Alice", 30, 1.65};
```

##### Assignation

You can assign a value to a structure using curly braces **{}**.
```
person_2 = {"Max", 25, 1.55};
```

##### Reading and Writing

You can access the members of a structure using the dot operator **(.)** followed by the member name. This allows you to read or modify the values stored in the structure's variables.
```
Person person_3;
person1.age = 55;
person1.height = 1.69;
```

##### Nested Structures

You can have structures within structures, creating nested or hierarchical data structures.
```
typedef struct {
    char street[50];
    char city[50];
    int  zipCode;
} Address;

typedef struct {
    char    name[50];
    int     age;
    float   height;
    Address address;
} Person;
```