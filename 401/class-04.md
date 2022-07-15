Classes and Objects

Objects are encapsulation of variables and functions into a single entity.
Objects get their variables and functions from classes.
Classes are essentially a template to create objects.
You can create multiple objects that are of the same classs.
Thinking Recursively in Python

A recursive function is a function defined in terms of itself via self-referential expressions.
This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result.
All recursive functions share a common structure made up of two parts: base case and recursive case.
Decompose the original problem into simpler instances of the same problem.
This is the recursive case.
As the large problem is broken down into successively less complex ones, those subproblems must eventually become so simple that they can be solved without further subdivision.
This is the base case.
Behind the scenes, each recursive call adds a stack frame (containing its execution context) to the call stack until we reach the base case.
Then, the stack begins to unwind as each call returns its results.