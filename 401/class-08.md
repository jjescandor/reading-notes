List comprehension

List comprehension is a powerful and concise method for creating lists in Python that becomes essential the more you work with lists, and lists of lists.
List comprehension methods are an elegant way to create and manage lists. 
In Python, list comprehensions are a more compact way of creating lists. 
More flexible than for loops, list comprehension is usually faster than other methods.
Let’s start by creating a list of numbers using Python list comprehensions. We’ll take advantage of Python’s range() method as a way to create a list of digits.

Example 1: Creating a list with list comprehensions

# construct a basic list using range() and list comprehensions
# syntax
# [ expression for item in list ]
digits = [x for x in range(10)]

print(digits)
Output

[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
Example 2: Comparing list creation methods in Python

First, create a list and loop through it. Add an expression, in this example, we’ll raise x to the power of 2.

# create a list using a for loop
squares = []

for x in range(10):
    # raise x to the power of 2
    squares.append(x**2)

print(squares)
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
Output

The same thing can be done using a list comprehension, but with a fraction of the code. Let’s take a look at how to create a list of squares using the list comprehension method.
# create a list using list comprehension
squares = [x**2 for x in range(10)]

print(squares)