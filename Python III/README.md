# Python III

# Error Handling
When an error occurs, or exception as we call it, Python will normally stop and generate an error message.

### Try and Except Statement
Try and except statements are used to catch and handle exceptions in Python. Statements that can raise exceptions are kept inside the try clause and the statements that handle the exception are written inside except clause.

### Catching Specific Exception
A try clause can have any number of except clauses to handle different exceptions, however, only one will be executed in case an exception occurs.
We can use a tuple of values to specify multiple exceptions in an except clause
* #### Using 2 Excepts
* #### Using Tuple

### Else Clause
It can also use the else clause on the try-except block which must be present after all the except clauses. The code enters the else block only if the try clause does not raise an exception.

### Finally Clause
Python provides a keyword finally, which is always executed after the try and except blocks. The final block always executes after normal termination of try block or after try block terminates due to some exception.


# Function
Python Functions is a block of statements that return the specific task.

### Define a Function
Create a  Python function using the def keyword.

### Calling a Function
After creating a function we can call it by using the name of the function followed by parenthesis containing parameters of that particular function.

### Return statement
The function return statement is used to exit from a function and go back to the function caller and return the specified value or data item to the caller. 

### Argument
Arguments are the values passed inside the parenthesis of the function. A function can have any number of arguments separated by a comma.

#### Argument and Parameter
* ##### A parameter is the variable listed inside the parentheses in the function definition.
* ##### An argument is the value that is sent to the function when it is called.

#### Number of Arguments
By default, a function must be called with the correct number of arguments. Meaning that if your function expects 2 arguments, you have to call the function with 2 arguments, not more, and not less.


### Pass by reference vs value
One important thing to note is, in Python every variable name is a reference. When we pass a variable to a function, a new reference to the object is created. Parameter passing in Python is the same as reference passing in Java.


### Lambda
A lambda function is a small anonymous function.
A lambda function can take any number of arguments, but can only have one expression.


# pydoc
The pydoc module automatically generates documentation from Python modules. The documentation can be presented as pages of text on the console, served to a web browser, or saved to HTML files.


# File Handling
File handling is an important part of any web application.
Python has several functions for Opening, reading, updating, creating, closing and deleting files.
### Open a File
The key function for working with files in Python is the open() function.

The open() function takes two parameters; filename, and mode.

* r: open an existing file for a read operation.
* w: open an existing file for a write operation. If the file already contains some data then it will be overridden.
* a:  open an existing file for append operation. It won’t override existing data.
* r+:  To read and write data into the file. The previous data in the file will be overridden.
* w+: To write and read data. It will override existing data.
* a+: To append and read data from the file. It won’t override existing data.

### Read a File
There is more than one way to read a file in Python. If you need to extract a string that contains all characters in the file then we can use file.read().
* ### .read()
By default the read() method returns the whole text
* ### .readline()
To read each line in the file can use .readline()
* ### .readlines()
To read all lines in the file but in the format of a list. so you can use .readlines()

### Write/Create a File
To write to an existing file, you must add a parameter to the open() function:

"a" - Append - will append to the end of the file

"w" - Write - will overwrite any existing content


### Close a File
To close an open file, use .close()

### Delete a File
To delete a file using library os and .remove()

# Library
A Python library is a collection of related modules. It contains bundles of code that can be used repeatedly in different programs. It makes Python Programming simpler and convenient for the programmer. As we don’t need to write the same code again and again for different programs.
### Math Library
Python has a built-in module called math, which extends the list of mathematical functions.

some of the function that can be used from the math library:
* #### pi, The math.pi method return 3.14(pi) value.
* #### ceil, The math.ceil() method rounds a number upwards to its nearest integer.
* #### floor, The math.floor() method rounds a number downwards to its nearest integer.
* #### sqrt, The math.sqrt() method returns the square root of a number.

### Datetime Library
The datetime module supplies classes for manipulating dates and times.

While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.

the notebook contains:
* #### get current time with today(),
* #### formatting with strftime().

### IO Library
The io module provides Python’s main facilities for dealing with various types of I/O.

This module is a part of the standard library, so there’s no need to install it separately using pip.

### Sys Library
The python sys module provides functions and variables which are used to manipulate different parts of the Python Runtime Environment. It lets us access system-specific parameters and functions.

### Numpy Library
NumPy is a Python library used for working with arrays.

In Python we have lists that serve the purpose of arrays, but they are slow to process.

NumPy aims to provide an array object that is up to 50x faster than traditional Python lists.

the notebook contains:
#### make a NumPy array
to make a NumPy array we can use np.array(), the value can be int, list, tuple, and other data typr in python.
#### Dimension in NumPy array
NumPy array can store multiple dimension of array.
#### get element of NumPy array 
to get an item from NumPy array we can use index just line acccing list or tuple in python.
here details how to get elements of array;
* slicing in NumPy array
* access list of multipe dimension
* access list of multiple dimension and slicing
