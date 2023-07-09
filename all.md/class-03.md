## What Is a File?
At its core, a file is a contiguous set of bytes used to store data.

Files on most modern file systems are composed of three main parts:

Header: metadata about the contents of the file (file name, size, type, and so on)
Data: contents of the file as written by the creator or editor
End of file (EOF): special character that indicates the end of the file


## File Paths :
The file path is a string that represents the location of a file. It’s broken up into three major parts:

Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
File Name: the actual name of the file
Extension: the end of the file path pre-pended with a period (.) used to indicate the file type
there is tow types of file paths:

Absolute Path: the full path from the root folder
Relative Path: the path relative to the current working directory


## Opening and Closing a File in Python :
file = open('path/to/file')
Remember : it’s your responsibility to close the file.

to avoid the problem of forgetting to close the file, we can use the with statement.

with open('path/to/file') as file:
    # do something with the file
NOTE : you can access the file variable outside the with block, but the file will be closed.

Other options for modes are fully documented online, but the most commonly used ones are the following:

Character Meaning

Character	Meaning
'r'	Open for reading (default)
'w'	Open for writing, truncating (overwriting) the file first
'rb' or 'wb'	Open in binary mode (read/write using byte data)
There are three different categories of file objects:

Text files
Buffered binary files
Raw binary files

## Reading and Writing Opened Files :
here are multiple methods that can be called on a file object to help you out

> file.read(size) # read the entire file
> file.readline(size) # read a single line
> file.readlines() # read remaining lines into a list
> file.write(string) # write a string to the file.

