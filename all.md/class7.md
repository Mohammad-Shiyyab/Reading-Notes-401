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