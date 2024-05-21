# Loops in Python
Python programming language provides two types of Python loopshecking time.Loops in Python provides three ways for executing the loops.While all the ways provide similar basic functionality, they differ in their syntax and condition-checking time.
# While Loop in Python
In Python, a while loop is used to execute a block of statements repeatedly until a given condition is satisfied. When the condition becomes false, the line immediately after the loop in the program is executed.

![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/87ff84aa-10f1-442e-8d2c-d541cfc161ec)


Python While Loop Syntax:

    while expression:

        statement(s)
    
# Using else statement with While Loop in Python
The else clause is only executed when your while condition becomes false. If you break out of the loop, or if an exception is raised, it won’t be executed. 

Syntax of While Loop with else statement:

    while condition:

         # execute these statements
     
    else:

         # execute these statements

Nested While Loop Syntax:

    while expression:

        while expression: 
            statement(s)
        
        statement(s)

# For Loop in Python
For loops are used for sequential traversal. For example: traversing a list or string or array etc. In Python, there is “for in” loop which is similar to foreach loop in other languages.

![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/1fb1ce35-69ab-45ae-ad78-1cd0d655f5e6)


For Loop Syntax:

    for iterator_var in sequence:

        statements(s)
    
Nested For Loops Syntax:

    for iterator_var in sequence:

        for iterator_var in sequence:
    
            statements(s)
        
        statements(s)
# Range Function
The Python range() function returns a sequence of numbers, in a given range. The most common use of it is to iterate sequences on a sequence of numbers using Python loops.

Syntax: 

    range(start, stop, step)

Parameter :

* start: [ optional ] start value of the sequence
* stop: next value after the end value of the sequence
* step: [ optional ] integer value, denoting the difference between any two numbers in the sequence
# Loop Control Statements
Loop control statements change execution from their normal sequence. When execution leaves a scope, all automatic objects that were created in that scope are destroyed. Python supports the following control statements.

What is the use of the range function in Python?

In simple terms, range() allows the user to generate a series of numbers within a given range. Depending on how many arguments the user is passing to the function, the user can decide where that series of numbers will begin and end, as well as how big the difference will be between one number and the next. Python range() function takes can be initialized in 3 ways.

* range (stop) takes one argument.
* range (start, stop) takes two arguments.
* range (start, stop, step) takes three arguments.

Python range (stop)

When the user call range() with one argument, the user will get a series of numbers that starts at 0 and includes every whole number up to, but not including, the number that the user has provided as the stop.

![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/ffdb3584-eec8-4be9-99b1-2046de35e77a)

Python range (start, stop)

When the user call range() with two arguments, the user gets to decide not only where the series of numbers stops but also where it starts, so the user doesn’t have to start at 0 all the time. Users can use range() to generate a series of numbers from X to Y using range(X, Y).

![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/eaa0caf2-2861-422d-901d-7e1a3b19b6fd)

Python range (start, stop, step)

When the user call range() with three arguments, the user can choose not only where the series of numbers will start and stop, but also how big the difference will be between one number and the next. If the user doesn’t provide a step, then range() will automatically behave as if the step is 1. In this example, we are printing even numbers between 0 and 10, so we choose our starting point from 0(start = 0) and stop the series at 10(stop = 10). For printing an even number the difference between one number and the next must be 2 (step = 2) after providing a step we get the following output (0, 2, 4, 8).

![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/a4288249-18a0-4d5c-8622-52e831b6ffe3)

# Continue Statement
The continue statement in Python returns the control to the beginning of the loop.

# Break Statement
The break statement in Python brings control out of the loop.

# Pass Statement
We use pass statement in Python to write empty loops. Pass is also used for empty control statements, functions and classes.
   
