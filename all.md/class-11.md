# Class 11: Data Analysis
-------------------------------------------------------------------------------

## What are the key features and benefits of Jupyter Lab, and how does it differ from Jupyter Notebook?
---------------------------------------------------------------------------

JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

the key features and benefits of Jupyter Lab are:

- JupyterLab is a next-generation web-based user interface for Project Jupyter.
- JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.
- JupyterLab also offers increased support for third-party extensions.

## What are the main functionalities provided by the NumPy library, and how can it be useful in Python programming, particularly for scientific computing and data manipulation tasks?
----------------------------------------------------------------------------------

NumPy is a Python library used for working with arrays, the main functionalities provided by the NumPy library are:

- It provides a high-performance multidimensional array object, and tools for working with these arrays.
- Lists Of Lists for CSV Data

it can be useful in Python programming, particularly for scientific computing and data manipulation tasks because:

- NumPy is the fundamental package for scientific computing in Python.
- It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
- NumPy arrays are stored at one continuous place in memory unlike lists, so processes can access and manipulate them very efficiently.
- NumPy is a Python library and is written partially in Python, but most of the parts that require fast computation are written in C or C++.

## Explain the basic structure and properties of NumPy arrays, and provide examples of how to create, manipulate, and perform operations on them
---------------------------------------------------------------------------------

- Creating A NumPy Array We can create a NumPy array using the numpy.array function.
```
import numpy as np

# Create a NumPy array
arr = np.array([1, 2, 3, 4, 5])

```

- NumPy Array Attributes The shape of an array is the number of elements in each dimension.
```
import numpy as np

# Create a NumPy array
arr = np.array([1, 2, 3, 4, 5])

print(arr.shape) # (5,)
```

The ndim attribute represents the number of array dimensions or the rank of the array.
```
print(arr.ndim) # 1

```

The size attribute is the number of elements in the array.

```
print(arr.size) # 5
```

Using NumPy To Read In Files
```
import numpy as np

# Load a CSV file
data = np.genfromtxt("winequality-red.csv", delimiter=";", skip_header=1)

```

- NumPy Array Indexing
```
import numpy as np

# Create a NumPy array
arr = np.array([1, 2, 3, 4, 5])

# Access the second element of the array
print(arr[1]) # 2
```

```
arr = np.array([1, 2, 3, 4, 5])
# Access the last element of the array
print(arr[-1]) # 5
```
```
arr = np.array([[1, 2, 3, 4, 5], [6, 7, 8, 9, 10]])
# Access the first element of the second array of the array
print(arr[1, 0]) # 6
```

- Converting Data Types
 ```
import numpy as np

# Create a NumPy array
arr = np.array([1.1, 2.1, 3.1])

# Convert the data type of the array
newarr = arr.astype('i')

print(newarr) # [1 2 3]
print(newarr.dtype) # int32

```
