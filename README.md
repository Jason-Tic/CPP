# Programming in C/C++ Efficiently

Course 'CS205 C/C++ Program Design' in 2021 Fall at Southern University of Science and Technology. The lecture videos can be found at https://www.bilibili.com/video/BV1Vf4y1P7pq

## [Chapter 1: Getting Started](week01/README.md) 

* [Lecture notes](week01/Lecture01.pptx)
* [Lab notes](week01/Lab01.pptx)
* [Examples](week01/examples)

## [Chapter 2: Data Types and Arithmetic Operators](week02/README.md)

* [Lecture notes](week02/Lecture02.pptx)
* [Lab notes](week02/Lab02.pptx)
* [Examples](week02/examples)

## [Chapter 3: Loops and Branching Statements](week03/README.md)

* [Lecture notes](week03/Lecture03.pptx)
* [Lab notes](week03/Lab03.pptx)
* [Examples](week03/examples)

## [Chapter 4: Data Structures](week04/README.md)

* [Lecture notes](week04/Lecture04.pptx)
* [Lab notes](week04/Lab04.pptx)
* [Examples](week04/examples)

## [Chapter 5: Memory and Pointer](week05/README.md)

* [Lecture notes](week05/Lecture05.pptx)
* [Lab notes](week05/Lab05.pptx)
* [Examples](week05/examples)

## [Chapter 6: Basics of Functions](week06/README.md)

* [Lecture notes](week06/Lecture06.pptx)
* [Lab notes](week06/Lab06.pptx)
* [Examples](week06/examples)

## [Chapter 7: Advances in Functions](week07/README.md)

* [Lecture notes](week07/Lecture07.pptx)
* [Lab notes](week07/Lab07.pptx)
* [Examples](week07/examples)

## [Chapter 8: Speedup Your Program](week08/README.md)

* [Lecture notes](week08/Lecture08.pptx)
* [Lab notes](week08/Lab08.pptx)
* [Examples](week08/examples)

## [Chapter 9: Basics of Classes](week09/README.md)

* [Lecture notes](week09/Lecture09.pptx)
* [Lab notes](week09/Lab09.pptx)
* [Examples](week09/examples)

## [Chapter 10: Advances in Classes](week10/README.md)

* [Lecture notes](week10/Lecture10.pptx)
* [Lab notes](week10/Lab10.pptx)
* [Examples](week10/examples)

## Chapter 11: Dynamic Memory Management in Classes

### Some Default Operations

* Default constructor
* Copy constructor
* Assign operator
* Default destructor
* How pointer members work by default

### An Example with Dynamic Data Allocation

### Solution

### Matrix Data Management in OpenCV

### Lab

Create a class for matrices which elements are in float. The class should support the follow operations and has no memory management problem. When a matrix is assigned to another by =, the two matrices will share the same data.
`class Matrix{...};`
`Matrix a(3,4);`
`Matrix b(3,4);`
`Matrix c = a + b;`
`Matrix d = a * 2.0f;`

## Chapter 12: Class Inheritance

### Deriving a Class

* Constructor
* Destructor

### Static and Dynamic Binding

### Vitural Functions

### Access Control (protected)

### Dynamic Memory Management

### Lab

## Chapter 13: Class Templates and std Library

### Defining a Class Template

### Templates in OpenCV

### Templates in std

### Lab

Create a matrix template class which can handle different data types.

## Chapter 14: Exceptions

## Chapter 15: Friend Classes and Nested Classes

## Reference
1. Mr. Yitong Wang's repo for the course in Fall 2020. https://github.com/YeeTone/CS205-2020Fall
