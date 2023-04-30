 

## A beginner's guide to Big O Notation:

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm. It can be used to describe the execution time or space used by an algorithm. Common orders of growth include O(1), O(N2), O(N3), O(N4), and O(2N). An example of an O(2N) function is the recursive calculation of Fibonacci numbers. Binary search is a technique used to search sorted data sets.

Logarithms:
It works by selecting the middle element of the data set and comparing it against a target value. If the target value is higher than the probe element, it will take the upper half of the data set and perform the same operation against it. Iterative halving of data sets produces a growth curve that peaks at the beginning and flattens out as the size of the data sets increases. This makes algorithms like binary search extremely efficient when dealing with large data sets.

Q1)

A-   Anyone who’s read Programming Pearls or any other Computer Science books and doesn’t have a grounding in Mathematics will have hit a wall when they reached chapters that mention O(N log N) 

B-    other seemingly bizarre syntax. Hopefully this article will help you gain an understanding of the basics of Big O and Logarithms.





Q2)

**concept of time complexity:

O(1)

O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

**concept space complexity :

O(N)

O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. The example below also demonstrates how Big O favours the worst-case performance scenario; a matching string could be found during any iteration of the for loop and the function would return early, but Big O notation will always assume the upper limit where the algorithm will perform the maximum number of iterations.