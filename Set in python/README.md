# Sets in Python
A Set in Python programming is an unordered collection data type that is iterable, mutable and has no duplicate elements. 
    Set are represented by { } (values enclosed in curly braces)
# Python Frozen Sets
* Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. It can be done with frozenset() method in Python.
* While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.
* If no parameters are passed, it returns an empty frozenset.
# Internal working of Set
* This is based on a data structure known as a hash table.  If Multiple values are present at the same index position, then the value is appended to that index position, to form a Linked List.
* In, Python Sets are implemented using a dictionary with dummy variables, where key beings the members set with greater optimizations to the time complexity.
# Set Implementation:
![image](https://github.com/user-attachments/assets/a4c406aa-f813-4de1-9012-a6ba57a50f0c)
# Sets with Numerous operations on a single HashTable:
![image](https://github.com/user-attachments/assets/6f578627-493c-4d62-a6ee-f1f4a4e76ef4)
# Creating a Set in Python
* Python Sets can be created by using the built-in set() function with an iterable object or a sequence by placing the sequence inside curly braces, separated by a ‘comma’.
* A set can also be created by using curly braces {} notation, containing the number 1,2 and 3.
