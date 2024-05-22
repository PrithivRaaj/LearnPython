# Strings
A String is a data structure in Python Programming that represents a sequence of characters. It is an immutable data type, meaning that once you have created a string, you cannot change it. Python String are used widely in many different applications, such as storing and manipulating text data, representing names, addresses, and other types of data that can be represented as text.
# What is a String in Python?
Python Programming does not have a character data type, a single character is simply a string with a length of 1. Let’s see the Python string syntax:

Syntax of String Data Type in Python

    string_variable = 'Hello, world!'

Creating a string in python

Strings in Python can be created using single quotes or double quotes or even triple quotes. 

# Accessing characters in Python String

 Individual characters of a String can be accessed by using the method of Indexing. Indexing allows negative address references to access characters from the back of the String, e.g. -1 refers to the last character, -2 refers to the second last character, and so on.
 While accessing an index out of the range will cause an IndexError. Only Integers are allowed to be passed as an index, float or other types that will cause a TypeError.
 
 ![image](https://github.com/PrithivRaaj/LearnPython/assets/111727780/b19aa2d3-a317-447b-9832-90de9bc9c6f6)

 # Python String Positive Indexing
 
 We will define a string in Python Programming and access its characters using positive indexing. The 0th element will be the first character of the string.

 # Python String Negative Indexing
 we will access its characters using negative indexing.

# String Slicing Python
The String Slicing method is used to access a range of characters in the String. Slicing in a String is done by using a Slicing operator, i.e., a colon (:).  One thing to keep in mind while using this method is that the string returned after slicing includes the character at the start index but not the character at the last index.
# Python String Reversed
 By accessing characters from a string, we can also reverse strings in Python Programming. We can Reverse a string by using String slicing method.
# BuildIn Reverse Function in Python
We can also reverse a string by using built-in join and reversed functions, and passing the string as the parameter to the reversed() function.
# Deleting/Updating from a String
In Python, the Updation or deletion of characters from a String is not allowed. This will cause an error because item assignment or item deletion from a String is not supported. Although deletion of the entire String is possible with the use of a built-in del keyword. This is because Strings are immutable, hence elements of a String cannot be changed once assigned. Only new strings can be reassigned to the same name. 

Updating a character

A character of a string can be updated in Python by first converting the string into a Python List and then updating the element in the list. As lists are mutable in nature, we can update the character and then convert the list back into the String.

Another method is using the string slicing method. Slice the string before the character you want to update, then add the new character and finally add the other part of the string again by string slicing.
# Escape Sequencing in Python
While printing Strings with single and double quotes in it causes SyntaxError because String already contains Single and Double Quotes and hence cannot be printed with the use of either of these. Hence, to print such a String either Triple Quotes are used or Escape sequences are used to print Strings. 

Escape sequences start with a backslash and can be interpreted differently. If single quotes are used to represent a string, then all the single quotes present in the string must be escaped and the same is done for Double Quotes.
# Python String Formatting
Strings in Python or string data type in Python can be formatted with the use of format() method which is a very versatile and powerful tool for formatting Strings. Format method in String contains curly braces {} as placeholders which can hold arguments according to position or keyword to specify the order.

# String Template Class in Python

