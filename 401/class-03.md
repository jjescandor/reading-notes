Reading and Writing Files in Python:

File - a file is a contiguous set of bytes used to store data.  A file consists of three main parts.

Header: metadata about the contents of the file (file name, size, type, and so on)
Data: contents of the file as written by the creator or editor
End of file (EOF): special character that indicates the end of the file
File Paths - when you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file. It’s broken up into three major parts:

Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
File Name: the actual name of the file
Extension: the end of the file path pre-pended with a period (.) used to indicate the file type
Links to an external site.

Extensions Vs. Syntax Errors

Syntax errors occur when the parser detects an incorrect statement

Exception errors occurs whenever syntactically correct Python code results in an error.

Raising an Exception

We can use raise to throw an exception if a condition occurs.

The statement can be complemented with a custom exception.

AssertionError Exception

Instead of waiting for a program to crash midway, you can also start by making an assertion in Python.

We assert that a certain condition is met. If this condition turns out to be True, then the program can continue.

If the condition turns out to be False, you can have the program throw an AssertionError exception.

try and except Block: Handling Exceptions

The try and except block in Python is used to catch and handle exceptions.

Python executes code following the try statement as a “normal” part of the program.

The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.