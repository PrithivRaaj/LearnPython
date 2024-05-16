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

Nested While Loop Syntax:

while expression:

   while expression: 
   
       statement(s)
       
   statement(s)

# For Loop in Python
For loops are used for sequential traversal. For example: traversing a list or string or array etc. In Python, there is “for in” loop which is similar to foreach loop in other languages.

For Loop Syntax:

for iterator_var in sequence:

    statements(s)
    
Nested For Loops Syntax:

for iterator_var in sequence:

   for iterator_var in sequence:
   
       statements(s)
       
   statements(s)
# Loop Control Statements
Loop control statements change execution from their normal sequence. When execution leaves a scope, all automatic objects that were created in that scope are destroyed. Python supports the following control statements.
# Continue Statement
The continue statement in Python returns the control to the beginning of the loop.

# Break Statement
The break statement in Python brings control out of the loop.

# Pass Statement
We use pass statement in Python to write empty loops. Pass is also used for empty control statements, functions and classes.
   
