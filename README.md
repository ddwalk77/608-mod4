# 608-mod4
Module 4 - Chapter 5 &amp; 6 practice, notes, &amp; project
### Chapter 5

Collections are prepackaged data structures consisting of related data items

List:

- Typically store homogeneous data, but can hold items of diffrent type, heterogeneous data
- Referenced by writing the list name followed by the element's index(position number) enclosed in square brackets ([] - subscription operators)
- The first element in a list has the index 0
- List length called using len function
- Access elements from the end of the list with negative indices
- An index must be an integer or integer expression (or slice)
- Modifiable (mutable) if numeric. String & Tuples sequences are immutable
- List elements may be used as variables in expressions
- Can dynamically resize as necessary with += When the left operand of += is a list, the right operand must be an iterable
- You can concatenate two lists, two tuples or two strings using the + operator. The original lists are unchanged.
- List elements can be accessed via their indices and the subscription operator ([]). The function call range(len(concatenated_list)) produces a sequence of integers representing the list indices
-You can compare entire list element by element using comparison operators

Tuples:

- Immutable - not modifiable
- Typically heterogeneous but it can be homogeneous
- Tuple's length is its number of elements and cannot change during program execution
- Create empty tuple with empty parentheses
- You can pack a tuple by separating values with commas
- Python always displays the contents of a tuple in parentheses, but you can add parentheses to the comma separated list if you wish
- One element tuple needs a comma to mark it as a tuple vs assigning a variable such as a string
- Tuple elements can be accessed individually. Like list, the indices start at 0
- Although immutable, the += augmented assignment statment can be used with strings & tubles and to append a list
- Tuples may contain mutable objects. Even though a tuple is immutable, its elements are mutable

Unpacking Sequences:

- You can unpack any tuple, string, list, or sequence by assigning it's elements to a comma-separated list of variables
- You can swap two variable values using sequence packing & unpacking
- enumerate is a built-in function that is preferred for accessing an element's index and value. The function receives an iterable and creates an iterator that, for each element, returns a tuple containing the element's index and value

Slices:

- "Slices (substrings) are super powerful for processing strings (stored as lists of characters).  You can process Romeo and Juliet and replace every occurrence of Romeo with your friends name. :)" - Dr Case
- You can slice sequences to create new sequences of the same type containing subsets of the original elements
- Slice operations can modify mutable sequences - those that do not modify a sequence work identically for lists, tuples, and strings
- Slices create new objects but they are shallow copies of the elements (they copy the elements' references but not the objects themselves)
- You can modify a list by assigning a slice to it

Del statement:
- The del statement can be used to remove elements from a list and to delete variables from the interactice session. You can remove the element at any valid index or the element(s) from any valid slice

Passing Lists to Functions:
- When passing a tuple to a function, attempting to modify the tuple's immutable elements results in a TypeError. Tuples may contain mutbale objects, such as lists. Thos objects cstill can be modified when a tuple is passed to a function.

Sorting Lists
- List method sort modifies a list to arrange its elements in ascending order
- To sort descending we call the sort function and add keyword reverse and set it to True
- Built in sorted returns a new list containing the sorted elements of its argument sequence
- lexicographical order - strings are compared by their character's numerical index - Upper cases letters are lower than lowercase values

Searching Sequences
- Searching is the process of locating a key value
- List method index takes as an argument a search key - the vlaue to locate in the list - then searches through the list from index 0 and returns the index of the first element that matches the search key
- You can use *= to multiply a sequence
- Can search using: example -numbers.index(value, start, end) # Specifying the Starting and Ending Indices of a Search
- Operator in tests whether its right operand's iterable contains the left operand's value
- Operator not in tests whether its right operand's iterable does not contain the left operand's value
- Use the operator in to ensure that calls to method index do not result in ValueError for search keys that are not in the corresponding sequence
- built in function any returns True if any item in its iterable argument is True
- built in function all returns True if all items in its iterable argument are True

### Chapter 6
