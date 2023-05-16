# class 07
----------------------------------------------------------------------------
## Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both
----------------------------------------------------------------------------
The concept of scope rules how variables and names are looked up in your code. It determines the visibility of a variable within the code. The scope of a name or variable depends on the place in your code where you create that variable

- Global scope: The names that you define in this scope are available to all your code.

- Local scope: The names that you define in this scope are only available or visible to the code within the scope.

## How do the global and nonlocal keywords work in Python, and in what situations might you use them?
---------------------------------------------------------------------------------
- The global keyword is used to define a variable inside a function as a global variable. This means that the variable can be accessed inside another function even if it is not defined inside that function.

- The nonlocal keyword is used to define a variable inside a nested function (function inside a function). This means that the variable can be accessed inside the nested function.

## In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis
-----------------------------------------------------------------------------------
the purpose of Big O notation is to describe the performance or complexity of an algorithm. so we can compare between algorithms and choose the best one, and we can know how much the algorithm will take time to run and how much memory it will take.
import random

def roll():
    return random.randint(1,6)

def count(amount):
    count_ = 0
    for i in range(1, amount+1):
        if roll() == 3:
            count_ += 1
    return count_

total = 0

for i in range(1, 366):
    total += count(i)

print(total)

The most important details in this text are related to float approximation, lists, for loops, indexes, adding values, removing items from lists, and len(list). For loops iterate over a list, while for loops iterate over a list. Indexes can be used to access values, add objects to the end of a list, or remove items from a list. Len(list) returns the length of a list.