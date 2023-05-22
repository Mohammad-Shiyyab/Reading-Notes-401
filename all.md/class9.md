# Class 09
--------------------------------------------------------------------------------

## What is the purpose of dunder methods in Python? Provide an example of a commonly used dunder method
----------------------------------------------------------------------
Dunder methods are special methods in Python that have two underscores before and after their name. They are also known as magic methods. Dunder methods let you emulate the behavior of built-in types.

commonly used dunder method is :

- **init** method, which is used to initialize a newly created object.
- **str** method, which is used to return a string representation of an object.
- **repr** method, which is used to return a printable representation of an object.
- **len** method, which is used to return the length of a sequence.
```
class StrSupport:
    def __str__(self):
        return "this class support str method"
obj = str(StrSupport()) #output: this class support str method
```
## In the video “AI Guru makes $238,800 with misleading paid course,” what was the main ethical issue raised concerning the use of developers’ work, and how might this have been avoided?
--------------------------------------------------------------------------------

The main ethical issue raised concerning the use of developers’ work is that the developer's work was used without his permission and without giving him credit. This could have been avoided by giving the developer credit for his work and asking for his permission to use it.

## Describe the Python statistics module and give an example of a function within the module that can be used to perform a common statistical operation
-----------------------------------------------------------------------------

The Python statistics module provides functions to perform mathematical statistics on numeric data. It is available in Python 3.4 and above. The statistics module provides functions to calculate mathematical statistics of numeric data. It has functions for calculating the mean, median, mode, standard deviation, variance

```
def model(x, y, z):
    return (3*x + 7*x*y - 5*y) / (11 * z)

n = 100_000
X = NormalDist(10, 2.5).samples(n, seed=3652260728)
Y = NormalDist(15, 1.75).samples(n, seed=4582495471)
Z = NormalDist(50, 1.25).samples(n, seed=6582483453)
quantiles(map(model, X, Y, Z))       
[1.4591308524824727, 1.8035946855390597, 2.175091447274739]
```