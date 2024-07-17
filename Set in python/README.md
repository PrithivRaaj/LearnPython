# Sets in Python
A Set in Python programming is an unordered collection data type that is iterable, mutable and has no duplicate elements. 
    Set are represented by { } (values enclosed in curly braces)
# Python Frozen Sets
* Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. It can be done with frozenset() method in Python.
* While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.
* If no parameters are passed, it returns an empty frozenset.
# Creating a Set in Python
* Python Sets can be created by using the built-in set() function with an iterable object or a sequence by placing the sequence inside curly braces, separated by a ‘comma’.
* A set can also be created by using curly braces {} notation, containing the number 1,2 and 3.
# Access Items
* You cannot access items in a set by referring to an index or a key.
* But you can loop through the set items using a for loop, or ask if a specified value is present in a set, by using the in keyword.
# Add Items
* Once a set is created, you cannot change its items, but you can add new items.
* To add one item to a set use the add() method.
# Add Sets
To add items from another set into the current set, use the update() method.
# Add Any Iterable
The object in the update() method does not have to be a set, it can be any iterable object (tuples, lists, dictionaries etc.).
# Remove Item
To remove an item in a set, use the remove(), or the discard() method.
* Note: If the item to remove does not exist, remove() will raise an error.
* Note: If the item to remove does not exist, discard() will NOT raise an error.
* You can also use the pop() method to remove an item, but this method will remove a random item, so you cannot be sure what item that gets removed.
* The return value of the pop() method is the removed item.
* Note: Sets are unordered, so when using the pop() method, you do not know which item that gets removed.
* The clear() method empties the set.
* The del keyword will delete the set completely.
# Join Sets
    # Union
    The union() method returns a new set with all items from both sets.
    You can use the | operator instead of the union() method, and you will get the same result.
    
    # Join Multiple Sets
    All the joining methods and operators can be used to join multiple sets.
    When using a method, just add more sets in the parentheses, separated by commas
