# Python Lists
Python Lists are just like dynamically sized arrays, declared in other languages (vector in C++ and ArrayList in Java). In simple language, a Python list is a collection of things, enclosed in [ ] and separated by commas. 
  * Ordered collection of data.
  * Lists are mutable type of datastructure
  * It can contain multiple type of data
  * Lists are iterable
  * List can be created using "[]" square brackets or by inbuilt function "list()" example L=[1,2,3] L is a list
# Accessing elements from the List
In order to access the list items refer to the index number. Use the index operator [ ] to access an item in a list. The index must be an integer. Nested lists are accessed using nested indexing. 
# Getting the size of Python list
Python len() is used to get the length of the list.
# Taking Input of a Python List
We can take the input of a list of elements as string, integer, float, etc. But the default one is a string.
# Adding Elements to a Python List
There are three methods:
 * Using append() method
 * Using insert() method
 * Using extend() method
  # Using append() method
   Elements can be added to the List by using the built-in append() function. Only one element at a time can be added to the list by using the append() method, for the addition of multiple elements with the
   append() method, loops are used.Tuples can also be added to the list with the use of the append method because tuples are immutable. Unlike Sets, Lists can also be added to the existing list with the use of
   the append() method.
  # Using insert() method
   append() method only works for the addition of elements at the end of the List, for the addition of elements at the desired position, insert() method is used. Unlike append() which takes only one argument, the
   insert() method requires two arguments(position, value). 
  # Using extend() method
   Other than append() and insert() methods, there’s one more method for the Addition of elements, extend(), this method is used to add multiple elements at the same time at the end of the list.
# Reversing a List
There are two methods:
 *  A list can be reversed by using the reverse() method in Python.
 *  Using the reversed() function (The reversed() function returns a reverse iterator, which can be converted to a list using the list() function.)
# Removing Elements from the List
There are two methods:
 * Using remove() method
 * Using pop() method
# Using remove() method
Elements can be removed from the List by using the built-in remove() function but an Error arises if the element doesn’t exist in the list. Remove() method only removes one element at a time, to remove a range of elements, the iterator is used. The remove() method removes the specified item.
# Using pop() method
pop() function can also be used to remove and return an element from the list, but by default it removes only the last element of the list, to remove an element from a specific position of the List, the index of the element is passed as an argument to the pop() method.
# Slicing of a List
We can get substrings and sublists using a slice. In Python List, there are multiple ways to print the whole list with all the elements, but to print a specific range of elements from the list, we use the Slice operation. 

Slice operation is performed on Lists with the use of a colon(:). 

   syntax:
      
      To print elements from beginning to a range use:
               
               [: Index]
      
      To print elements from end-use:
      
               [:-Index]
     
      To print elements from a specific Index till the end use:

               [Index:]

      To print the whole list in reverse order, use 

               [::-1]
               
