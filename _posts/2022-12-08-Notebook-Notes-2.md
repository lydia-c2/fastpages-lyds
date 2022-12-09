--- 

description: Week 2 Lesson Notes and Vocab
title: Week 2 Lesson Notes and Vocab
toc: false
comments: true
permalink: /markdown/Week2Notes
categories: [week 15]
nb_path: _markdown/Week2
layout: notebook

---


# Unit 2 Binary/Data Terms

#### Bits: 
A bit is a "binary digit," which is a piece of data (smallest unit) for a computer to store.
- EX: 001, 011, 111, etc.

#### Bytes: 
"Binary Term," which stores single characters 
- EX: 1 byte = 8 bits 
- EX: kilobytes, megabytes, gigabytes

#### Hexadecimal / Nibbles:
A numbering system with a base of 16
- Hexadecimals go from 0-9 and A-F

#### Binary Numbers: 
Unsigned Integers: Are positive numbers (and 0) that do not require a sign bit. 

Signed Integer: Can contain the value 0 and positive and negative numbers. 
- Signed and unsigned integers are determined by the leading digit of a binary number

Floating Point: Floating points are whole integers (positive or negative) that also have a decimal point.
- EX: 2.5, 7.85, etc.
- EX: NOT 10, 4, 0...

#### Binary Data Abstractions: 
Boolean: A Boolean is a system of algebraic notation that represents logical propositions
- Booleans are also conditionals, testing whether a statement is true or false

ASCII: Short for "American Standard Code for Information Interchange," ASCII is the standard format for data exchange between computers.

Unicode: Like ASCII, Unicode is a standard encoding format but for international use between different scripts and languages.

RGB: Stands for Red, Green, Blue, which is the system for colors within a computer.
- Each color value goes from 0-255

#### Data Compression: 
Lossy: Data is permanently lost and cannot be recovered after decompression
- EX: JPEG, photo compression, etc
Lossless: (not discussed yet)

![]({{site.baseurl}}/images/LossyImage.png)





# Unit 3 Algorithm/Programming Terms

#### Variables:
Variables are place holders for pieces of data. The variable stores whatever is added into it, it could be code or integers or both.
- EX: x = 20

#### Data Types: 
Values or operations like strings, integers, booleans, characters, etc.

#### Assignment Operators:
An assignment operator is an equal sign, or a symbol, which is needed in order to store a value inside a variable.
- Stores value inside variable

#### Managing Complexity with Variables:  
Lists: Lists are sequences of elements where every element = a variable
2D Lists: Can be defined as a matrix with two dimensions, the rows and columns
- Also an array (data structure used to store elements)
- An array can only store similar types of elements
Dictionaries: Dictionaries are used to store data values in key
Class: An outline used when creating a new product

![]({{site.baseurl}}/images/ManagingComplexityList.png)

#### Algorithms: 
An algorithm is the instructions for the code to execute

#### Sequence: 
A sequence is the order in which the algorithm will run. 

#### Selection:
Selection is the code that will execute depending on whether or not the conditional is true or false.
- EX: "print("This is for APSCP")" if a conditional was true would be the SELECTION part of code

#### Iteration: 
An iteration is a repeating portion of an algorithm
- repeats a specified number of times or until a given condition is met

#### Expressions & Comparison Operators:
Comparison operators can compare numbers or strings and perform evaluations. 
- Expressions that use comparison operators do not return a number value as do arithmetic expressions

#### Booleans Expressions and Selection:
- Boolean expressions are conditional statements that are true or false

#### Booleans Expressions and Iteration:
- Boolean expressions are conditional statements that are true or false
#### Truth Tables:
- displays the logical operations on input signals in a table format.

#### Characters, Strings, Length:
- Characters are symbols or alphabetic letters
- Strings are sequences of characters
- Length is the number of symbols output when an procedure executes

#### Concatenation:
When two strings join together

#### Upper, Lower, Traversing Strings:
Upper() and Lower() converts characters in strings to either uppercase or lowercase
- Traversing strings is to process each part or character within a string (usually R to L)

#### Python If, Elif, Else conditionals; Nested Selection Statements:
If, Elif, and Else conditionals allow the procedure to check whether the conditions are true, and if so, to execute the code. Else is what code is run when none of the if or elif statements are met.

![]({{site.baseurl}}/images/FlowCode2.png)

#### Python For, While loops with Range, with List: 
For and while loops allow for a code to repeat without having to type out the code multiple times.
- While loops allow a procedure to repeat while the statement is true.
- For loops using lists allow you to pull variables from within the lists or whatever has been appended into the list

![]({{site.baseurl}}/images/FlowCode1.png)

#### Combining loops with conditionals to Break, Continue:
Break allows while loops to stop if a condition is met
- If a while loop is true, it will continue until it is broken

#### Procedural Abstraction, Python Def procedures:
"Def" is used to create function variables

#### Parameters, Return Values:
- Parameters are independent variables that allow a procedure to execute without knowing specific input values at the moment. 
    - For example, in "multiply(x,y)" x and y would be the parameters
- Python to continues executing the program and returns a certain value (Return Value)
    - Using a return statement 




# Lesson 3.5-7 Notes:

### Boolean:
- A Boolean is a system of algebraic notation that represents logical propositions
- Booleans are also conditionals, testing whether a statement is true or false

### Relational Operators:
- Mathematical relationships between variables
- EX: <, >, =

### Logical Operators:

- NOT: displays opposite of data
- AND: evaluates two conditionals together
- OR: evaluates conditionals and if one is true then code will execute

### KEY TERMS
Selection: Selection is the code that will execute depending on whether or not the conditional is true or false.
- EX: "print("This is for APSCP")" if a conditional was true would be the SELECTION part of code


Algorithm: An algorithm is the instructions for the code to execute
- EX: the code written below is an ALGORITHM


Conditional Statement / If-Statement: (Depends on boolean value) This statement determines whether or not the selected code will run. If the conditional is true, then the code will execute. If false, then it will not.
- EX: CONDITIONAL seen in code below (if test1 >= 75...)



[Lesson 3.5-3.7 Hacks](https://lydia-c2.github.io/lyds.github.io/markdown/U3L3Hacks)



# Lesson 3.8 & 3.10 Notes

##### What is an iteration?

An iteration is a repeating portion of an algorithm
- repeats a specified number of times or until a given condition is met

##### Iteration example

EX: Seeing which mailbox the key fits in
1. m = number of mailboxes
2. Mailbox number 1-m
3. Try key in mailbox
4. Try next mailbox (next highest)
5. Repeat until key fits
6. Get your mail!

STOPPING CONDITION: use "break" to stop the iteration

![]({{site.baseurl}}/images/Baddies4Life.png)

VOCAB:
- insert( ) allows a value to be inserted into a list at index i
- append( ) allows a value to be added at the end of a list 
- remove( ) allows an element at index i to be deleted from a list
- length( ) returns the number of elements currently in a specific list

##### a <-- EXPRESSION 
- Moves whatever "expression" is into the variable "a"

##### LIST <-- []
- Creates an empty list under the variable "LIST" 
- Allows you to add elements via "append"
- Append is APPEND(LIST, x)

##### List[i]
- "i" is where you would access the list (EX: index[1])

##### LENGTH(list)
- Evaluates the number of elements in the list

[Lesson 3.8 & 3.10 Hacks](https://lydia-c2.github.io/lyds.github.io/markdown/U3L5Hacks)


# Lesson 3.9 & 3.11 Notes

- Different algorithms can be used to achieve the same goal
- This is important within collaborating
    - Allows for debugging

![]({{site.baseurl}}/images/FlowChart1.png)

1. Start
2. Regionals = 26 places
3. Competitions = 0-5
5. If competitions>= 2
- Choose random place (out of 40)
- If place is < 26
- Print(Qualified)
6. If competitions<2:
- Print(Ineligible)

