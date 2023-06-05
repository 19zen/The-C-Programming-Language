# Enums

### Introduction

In C, an enum (enumeration) is a user-defined data type that allows you to define a set of named values. Enums provide a way to assign a symbolic name to a set of related constants, making the code more readable and maintainable.

### Declaration

To define an enum, you use the enum keyword followed by the enum's name. Inside the enum, you list the names of the constants (also called enumeration constants or enum members) enclosed in curly braces.
```
enum { SPRING, SUMMER, AUTUMN, WINTER } Season;
```

### Assignation

By default, the first enum member is assigned the value 0, and subsequent members are assigned values that increment by 1. However, you can explicitly assign values to enum members.
```
enum Days { MONDAY = 1, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY, SUNDAY };
```

### Reading and Writing

You can use enum members as symbolic constants throughout your code. Enum members are treated as integers, and you can compare them, assign them to variables, and perform arithmetic operations with them.
```
enum Season currentSeason = SUMMER;
if (currentSeason == SUMMER) {
    printf("Enjoy the sunny weather!\n");
} else {
    printf("I hope the sun will come back soon...\n");
}
```