# Function
Python Functions is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and 
again for different inputs, we can do the function calls to reuse code contained in it over and over again.

Some Benefits of Using Functions:

* Increase Code Readability 
* Increase Code Reusability

# Python Function Declaration
The syntax to declare a function is:

![image](https://github.com/user-attachments/assets/9d999030-415c-450d-ad1b-7662397b8df9)

Types of Functions in Python

Below are the different types of functions in Python:

* Built-in library function: These are Standard functions in Python that are available to use.
* User-defined function: We can create our own functions based on our requirements.

# Intro to functions: a simple example
We begin with a simple example of a function. The add_three() function below accepts any number, adds three to it, and then returns the result.
      # Define the function
      def add_three(input_var):
        output_var = input_var + 3
        return output_var
Every function is composed of two pieces: a header and body.

![image](https://github.com/user-attachments/assets/2a440f98-0007-4ff9-8037-f78c5a7a6a86)

# Header¶
The function header defines the name of the function and its argument(s).

* Every function header begins with def, which tells Python that we are about to define a function.
* In the example, the function name is add_three.
* In the example, the argument is input_var. The argument is the name of the variable that will be used as input to the function. It is always enclosed in parentheses that apppear immediately after the name of the function. (Note that a function can also have no arguments, or it can have multiple arguments. You'll see some examples of this later in the lesson.)
* For every function, the parentheses enclosing the function argument(s) must be followed by a colon :.
# Body
The function body specifies the work that the function does.

* Every line of code in the function body must be indented exactly four spaces. You can do this by pushing the space bar four times, or by hitting the "Tab" button once on your keyboard. (As you learn more about Python, you may need to indent your code by more than four spaces, but you'll learn more about that later in this course.)
* The function does its work by running all of the indented lines from top to bottom.
    *It takes the argument as input, which in the example is input_var.
    *The function creates a new variable output_var with the calculation output_var = input_var + 3.
    *Then, the final line of code, called the return statement, just returns the value in output_var as the function's output.
The code cell above just defines the function, but does not run it. The details of the function body will make more sense after the next code cell, when we actually run the function.
# How to run (or "call") a function¶
When we run a function, it can also be referred to as "calling" the function.
In the code cell below, we run the function with 10 as the input value. We define a new variable new_number which is set to the output of the function.

