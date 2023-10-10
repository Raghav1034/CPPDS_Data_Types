# CPPDS_Data_Types
Description of some basic data types in C++

# C++ Data Types

This repository contains examples and explanations of data types in C++. Understanding data types is fundamental to programming in C++, as they define the kind of data a variable can hold. This README provides an overview of commonly used data types in C++ and how to use them.

## Table of Contents
- [Data Types](#data-types)
  - [Built-in Data Types](#built-in-data-types)
  - [User-Defined Data Types](#user-defined-data-types)
- [Variable Declaration](#variable-declaration)
- [Sizeof Operator](#sizeof-operator)


## Data Types

### Built-in Data Types

C++ provides several built-in data types, including:

1. *int*: Represents integer values, e.g., `int myInt = 42;`.
2. *float*: Represents floating-point numbers, e.g., `float myFloat = 3.14;`.
3. *double*: Represents double-precision floating-point numbers, e.g., `double myDouble = 2.71828;`.
4. *char*: Represents single characters, e.g., `char myChar = 'A';`.
5. *bool*: Represents boolean values, which can be either `true` or `false`, e.g., `bool myBool = true;`.

### User-Defined Data Types

You can also define your own data types using structs, enums, and classes.

- *Structs*: Groups related variables under a single name. Example:
  cpp
  struct Point {
      int x;
      int y;
  };
  

- *Enums*: Define a set of named integral constants. Example:
  cpp
  enum Color {
      RED,
      GREEN,
      BLUE
  };
  

- *Classes*: Blueprint for creating objects. Example:
  cpp
  class Car {
  public:
      string make;
      string model;
      int year;
  };
  

## Variable Declaration

To declare a variable in C++, specify the data type followed by the variable name.

cpp
int age = 30;
float pi = 3.14159;
char grade = 'A';
bool isStudent = true;



## Sizeof Operator

You can determine the size (in bytes) of a data type using the `sizeof` operator:
cpp
int sizeOfInt = sizeof(int); // Returns the size of an int


### OUTPUT image: 
![image](<img width="237" alt="image" src="https://github.com/Raghav1034/CPPDS_Data_Types/assets/120126472/f017c0b4-05cc-481f-8001-79799b47afbf">
)




