# Loops in Python
Python programming language provides two types of Python loopshecking time.Loops in Python provides three ways for executing the loops.While all the ways provide similar basic functionality, they differ in their syntax and condition-checking time.
# While Loop in Python
In Python, a while loop is used to execute a block of statements repeatedly until a given condition is satisfied. When the condition becomes false, the line immediately after the loop in the program is executed.

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

# Infinite While Loop in Python

If we want a block of code to execute infinite number of time, we can use the while loop in Python to do so.

The code uses a ‘while' loop with the condition (count == 0). This loop will only run as long as count is equal to 0. Since count is initially set to 0, the loop will execute indefinitely because the condition is always true.
