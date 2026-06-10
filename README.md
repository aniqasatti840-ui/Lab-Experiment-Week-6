# OOP Lab Manual

## Week 06

### Experiment 01

Write a class definition `ComplexNumber` with two data members:

- realPart
- imaginaryPart

We wish to perform addition, subtraction, and multiplication with objects of the `ComplexNumber` class.

A complex number:

```text
c = a + bj
```

consists of two parts:

- Real Part (a)
- Imaginary Part (bj)

Arithmetic operations on complex numbers are defined as follows:

#### Addition (+)

```text
(a1 + b1j) + (a2 + b2j) = (a1 + a2) + (b1 + b2)j
```

#### Subtraction (-)

```text
(a1 + b1j) - (a2 + b2j) = (a1 - a2) + (b1 - b2)j
```

#### Multiplication (*)

```text
(a1 + b1j) * (a2 + b2j) = (a1a2 - b1b2) + (a1b2 + a2b1)j
```

Create objects of this class and test all the member functions.

---

### Experiment 02

The objective of this exercise is to learn the friend function of a class.

Create a class `Room` with the following members:

```cpp
width : double
printWidth(Room) : friend void
setWidth(double) : void
```

#### Procedure

1. Create an object of the `Room` class.
2. Call the `setWidth()` function and pass `10.10` as the argument value.
3. Print the width of the room by calling the `printWidth(Room)` function.
4. Since `printWidth(Room)` is a friend function, it will not be a member of the class.
5. Define the friend function outside the class instead of using the scope resolution operator (`::`).

---

### Experiment 03

Create a class named `Student` which can save student information containing:

- Roll Number
- First Name
- Last Name
- Student Class
- Total Marks
- Grade

Set default values for all class members in the default constructor.

All class members should be private and no getter/setter functions should be created to access them.

#### Requirements

1. Overload the constructor to initialize private class members with user-provided values.
2. Create a function `DisplayClassData`.
3. The function should accept the address of a Student class object as an argument.
4. Display all private data members within this function.

---

## Learning Objectives

After completing these experiments, students will be able to:

- Implement complex number arithmetic using classes.
- Understand and use friend functions.
- Work with private data members.
- Apply constructor overloading.
- Pass objects and object addresses to functions.
- Design object-oriented solutions using classes.

## Technologies Used

- C++
- Classes and Objects
- Friend Functions
- Constructor Overloading
- Encapsulation
- Complex Number Operations
