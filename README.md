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

### Chapter 6
