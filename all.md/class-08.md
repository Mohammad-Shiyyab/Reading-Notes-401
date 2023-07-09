# Class 08
----------------------------------------------------------------
## What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers
------------------------------------------------------------------
newlist = [expression for item in iterable if condition == True]

In general, list comprehensions tend to be more efficient than using for loops to create lists. This is because list comprehensions are optimized for Python's interpreter, and the operations performed in the comprehension are executed at C speed, making them faster than equivalent operations performed using a for loop.

Example: that squares the elements

nums = [1 , 2 , 3 , 4 , 5]
sq = [x * x for num in nums]  #output: [1, 4 , 9, 16, 25]

## What is a decorator in Python?
-----------------------------------------------------------------------

By definition, a decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.


# Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading
-------------------------------------------------------------------------

a decorator is a function that takes another function as an argument, adds some functionality to it, and then returns the original function. Decorators provide a way to modify the behavior of a function or class without changing its source code. They are commonly used for logging, debugging, profiling, and authentication.

A decorator function takes a function or class as input and returns a new function or class that wraps the original one. When the decorated function or class is called, the wrapper function is executed instead, which can perform some actions before or after the original function or class is called.