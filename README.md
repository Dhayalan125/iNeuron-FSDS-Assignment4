# iNeuron-FSDS-Assignment4

1. What exactly is []?
Ans: List object will be created within this square bracket []

2. In a list of values stored in a variable called spam, how would you assign the value 'hello' as the third value? (Assume [2, 4, 6, 8, 10] are in spam.)
Ans: spam[2] = ”hello”

Let's pretend the spam includes the list ['a', 'b', 'c', 'd'] for the next three queries.
3. What is the value of spam[int(int('3' * 2) / 11)]?
Ans: d

4. What is the value of spam[-1]?
Ans:d

5. What is the value of spam[:2]?
Ans: [‘a’,’b’]

Let's pretend bacon has the list [3.14, 'cat,' 11, 'cat,' True] for the next three questions.
6. What is the value of bacon.index('cat')?
Ans: 1

7. How does bacon.append(99) change the look of the list value in bacon?
Ans: [3.14, 'cat', 11, 'cat', True, 99]

8. How does bacon.remove('cat') change the look of the list in bacon?
Ans:  [3.14, 11, 'cat', True, 99]

9. What are the list concatenation and list replication operators?
Ans: The operator for list concatenation is +, while the operator for replication is *. (This is the same as for strings.)

10. What is difference between the list methods append() and insert()?
Ans: The only difference between append() and insert() is that insert function allows us to add a specific element at a specified index of the list unlike append() where we can add the element only at end of the list.

11. What are the two methods for removing items from a list?
Ans:
There are three ways in which you can Remove elements from List:
Using the remove() method.
Using the list object's pop() method.
Using the del operator.

12. Describe how list values and string values are identical.
Ans: The values that make up a list are called its elements. Lists are similar to strings, which are ordered collections of characters, except that the elements of a list can have any type and for any one list, the items can be of different types.

13. What's the difference between tuples and lists?
Ans: 
1	Lists are mutable	Tuples are immutable
2	Implication of iterations is Time-consuming	The implication of iterations is comparatively Faster
3	The list is better for performing operations, such as insertion and deletion.	Tuple data type is appropriate for accessing the elements
4	Lists consume more memory	Tuple consume less memory as compared to the list
5	Lists have several built-in methods	Tuple does not have many built-in methods.
6	The unexpected changes and errors are more likely to occur	In tuple, it is hard to take place.

14. How do you type a tuple value that only contains the integer 42?
Ans: (42,) (The trailing comma is mandatory)

15. How do you get a list value's tuple form? How do you get a tuple value's list form?
Ans:
List to tuple: tuple(list name)
Tuple to list: Using list comprehension along with zip() function

16. Variables that "contain" list values are not necessarily lists themselves. Instead, what do they contain?
Ans: It may contain int, str, tuple, float and etc.

17. How do you distinguish between copy.copy() and copy.deepcopy()?
Ans: copy.copy() is shallow copy of the original. We can modify the elements in the copy. But that’s not possible in the deep copy.
