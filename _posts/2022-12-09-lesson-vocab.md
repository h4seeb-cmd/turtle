---
title: Student Lesson Vocabulary
toc: true
branch: master
badges: true
comments: true
author: Haseeb Beg
categories: [fastpages, jupyter, Week 15] 
layout: post
---

# Unit 2… Binary/Data Terms
- Bits: The smallest unit of data that a computer can process and solve
- Bytes: Unit of data that is 8 binary digits long
- Hexadecimal: Numbering system that uses base 16
- Nibbles: 4 consectutive binary digits
- Binary Numbers: Numbering system that just uses 1s and 0s
- Unsigned Integer: Integers but have the property that they have a sign attached to them
- Signed Integer: 32 bit data that encodes an integer in a specific range
- Floating Point: Positive or negative whole numbers
#### Binary Data Abstractions: 
- Boolean: True or false statements
- ASCII: American Standard Code for Information interchange, a standard data-encoding format for electronic communication between computers
- Unicode: International encoding standard for use with different languages and scripts, by which each letter, digit, or symbol is assigned a unique numeric value that applies across different platforms and programs
- RGB: RGB (red, green, and blue) refers to a system for representing the colors to be used on a computer display. Red, green, and blue can be combined in various proportions to obtain any color in the visible spectrum. Levels of red, green, and blue can each range from 0 to 100 percent of full intensity.
### Data Compression: 
- Lossy, Lossless (not discussed)
# Unit 3… Algorithm/Programming Terms
- Variables: Values that can change, depending on the conditions and code written. Often assigned by the programmer.
- Data Types: A particular kind of data item, can be defined by the values it can take, the programming language used, or the operations that can be performed on it. 
- Assignment Operators: Used to assign values, functions, and variables to something. 
### Managing Complexity with Variables:  
- Lists: A sequence of several variables, grouped together under a single name.
- 2D Lists: A two-dimensional list can also be used to store objects, which is especially convenient for programming sketches that involve some sort of “grid” or “board”
- Dictionaries: A dictionary has a set of keys and each key has a single associated value
- Class: Extensible program-code-template for creating objects, providing initial values for state and implementations of behavior
- Algorithms: Step-by-step procedure that defines a set of instructions that must be carried out in a specific order to produce the desired result
- Sequence: Order that commands are executed by a computer, allows us to carry out tasks that have multiple steps
- Selection: Programming construct where a section of code is run only if a condition is met
- Iteration: Sequence of instructions or code being repeated until a specific end result is achieved
- Expressions: A combination of values and functions that are combined and interpreted by the compiler to create a new value
- Comparison Operators: Operators that compare two expressions and return a Boolean value that represents the relationship of their values
- Booleans Expressions and Selection: Ture or false, compares data of any type as long as types are the same. 
- Booleans Expressions and Iteration: and/or, not.
- Truth Tables: a way of summarising and checking the logic of a circuit. The table shows all possible combinations of inputs and, for each combination, the output that the circuit will produce. You can produce truth tables for parts of a circuit to check the logic at any stage.
- Characters: Display unit of information equating to one alphabetic letter or symbol
- Strings: Traditionally a sequence of characters, either as a literal constant or as some kind of variable
- Length: Code which maps source symbols to a variable number of bits
- Concatenation: Means obtaining a new string that contains both of the original strings 
- If: A conditional statement that only runs the code specified unless the defined conditons are met
- Else: Use else to specify a block of code to be executed, if the same condition is false
- Elif: used in conditional statements (if statements), and is short for else if
- Nested Selection Statements: Used when more than one decision must be made before carrying out a task
- Traversing Strings: To traverse a string means to accessing all the elements of the string one after the other by using the subscript. A string can be traversed using for loop or while loop.
- Upper: Upper bounds of a function
- Lower: Lower bounds of a fucntion
### Python If, Elif, Else conditionals; Nested Selection Statements
- Python For: A statement that is used to repeatedly execute code as long as the condition is satisfied.
- While loops with Range: A loop that itereates through the code specified in it's body
- Combining loops with conditionals to Break: 
- Continue: Code that is written when the programmer wants to force the program to move on
- Procedural Abstraction: Breaking up code in different pieces to add modularity with procedures
- Python Def procedures: Def is used when defining a function/procedure in python
- Parameters: Input values that help functions and procedures know what values to work with.
- Return Values: What a procedure gives as an output/resut.

### Search
- Sequential Search: search method that iterates through each index of a series of data (inefficient compared to binary)
- Binary Search: A search method that checks the median of a series of data to find the target value. If it's less than the median, than the search algorithm ignores the median and anything greater and repeats. Vice versa if the target is greater than the median.
### Calling/Developing Procedures
This was the lesson my group and I taught. See group fastpages for vocab.
### Libraries
- Library: A database that contains many different procedures and functions. They are imported through packages.
- Packages: A collection of methods that do certain things.
- Documentation: Helpful written explanations to what certain packages in libraries do. 
### Random Values
- Random Values : a number generated using a large set of numbers and a mathematical algorithm which gives equal probability to all number occuring,
### Simulations
- Simulation: Imitation of a situation or process that works like a virtual experiment
    -  Abstractions that mimic more complex objects or phenomena from the real world to draw inferences about things we cant observe
### Algorithmic Efficiency and Undecidable Problems
- Problem: A general description of a task that can or cannot be solved algorithmically
    - Decision Problem: A problem with a yes or no answer
    - Organization Problem: A problem with the goal of finding the best answer
- Instance: A problem with a specific input
- Efficiency: Amount of computing needed to solve a problem
    - Polynomial Efficiency (Good): More work take sa proportional amount of time. 1 job = +2 time
    - Exponential Efficiency (Bad): More work takes an exponential amount of time. 1 job = x2 time
- Heuristic Approach: When optimal solutions are inefficient, look for a possibly optimal solution that is more effecient
- Decidable Problem: A decision problme that has a clear solution that will always make a correct output
- Undecidable Problem: A decision problem with no solution that is not guaranteed to produce the correct output