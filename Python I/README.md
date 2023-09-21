# Introduction to Python


Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically-typed and garbage-collected. It supports multiple programming paradigms, including structured, object-oriented and functional programming.

#### Why Python?
* Easy to Learn and Use
* Hundreds of Python Libraries and Frameworks
* Versatility, Efficiency, Reliability, and Speed
* First-choice Language
* The use of python in academics
* The Flexibility of Python Language

## Variable 

A Python variable is a symbolic name that is a reference or pointer to an object.

Once an object is assigned to a variable, you can refer to the object by that name. However, the data is still contained within the object. The equal symbol (=) is used to assign values to variables. The operation to the left of the equals sign is the variable's name, and the operation to the right of the equals sign is the value stored in the variable.

## Data Type

Python has three basic data types: numeric, strings, and boolean.
* ### Numeric

#### Integers
* An integer is a whole number with no decimal places.
* For example, 10 is an integer, but 10.0 isn’t.
* The name for the integer data type is **int**.

#### Floating-point numbers
* A floating-point number, or float, is a number with a decimal place.
* 10.0 is a floating-point number, as is -0.25.
* The name of the floating-point data type is float.

####  Complex numbers
* The complex data type in python consists of two values, the real part of the complex number and the imaginary part of the complex number.

* ### String
A string is an array data structure of words (or bytes) that stores a sequence of elements, typically alphabets, words or other characters. 

* ### Boolean
Boolean refers to a system of logical thought that is used to create true/false
statements.

We may use the type() method to determine the data type of an object.

## Advanced  Data Type
### List
Lists are used to store multiple items in a single variable. 
* Lists are defined as objects with the data type 'list'
* It's ordered, changeable, and allow duplicate values.
* The first item has index [0], the second item has index [1] etc.
* It's created using square brackets. 

### Set
Sets are used to store multiple items in a single variable.
* Sets cannot have two items with the same value.
* A set is a collection which is unordered, unchangeable (but you can remove items and add new items), and unindexed.
* It's written with curly brackets.

### Tuple
Tuples are used to store multiple items in a single variable. 
* It's ordered, unchangeable, and allow duplicate values. 
* The first item has index [0]
* the second item has index [1] etc.
* It's written with round brackets.

### Dictionary
Dictionaries are used to store data values in pairs.
* It is ordered (In Python 3.6 and earlier, dictionaries are unordered), changeable, and do not allow duplicates.
* It's written with curly brackets, and have keys and values.

## Type Conversion
* ### Implicit Type Conversion
Automatically converts one data type to another without any user involvement.
* ### Explicit Type Conversion
In explicit type conversion, the data type is manually changed by the user as per their requirement.

## Argument Specifiers
The "%" operator is used to format a set of variables enclosed in a "tuple" (a fixed size list), together with a format string, which contains normal text together with "argument specifiers", special symbols like "%s" and "%d".
Some basic argument specifiers you should know:

* %s - String (or any object with a string representation, like numbers)

* %d - Integers

* %f - Floating point numbers

* %.<number of digits>f - Floating point numbers with a fixed amount of digits to the right of the dot.

* %x/%X - Integers in hex representation (lowercase/uppercase)

## Input and Output in Python

### Input
To take user input, use the input() function. We can use it to:
* Get user input with a message
* Integer input
* Take Multiple Inputs

### Output
* Python Output Using print() function
* Python Print output with custom sep and end parameter
#### Output Formatting
* Using format(), With this output format, the curly braces { } work as placeholders.
* Using % Operator, % values are replaced with zero or more value of elements.

## String Formatting
* ### zfill()
The zfill() method adds zeros (0) at the beginning of the string, until it reaches the specified length. If the value of the len parameter is < the length of the string, there will be no filling.

* ### Right Align | rjust()
This method right aligns the string according to the width specified and fills remaining space of line with blank space.

* ### Left Align | ljust()
This method left aligns the string according to the width specified and fills remaining space of line with blank space.

* ### Center Align | center()
This method center aligns the string according to the width specified and fills remaining space of line with blank space.

## String Literal
There's a way to use an apostrophe inside a string literal.
* Use double quote instead of single quote
* Use backslash as an escape character before the apostrophe

## Raw Strings
You can use r before a string starts to write a string as it is.
  
  ## Number, Character, and String Transformation
* ### Uppercase
The upper() method on a string converts all of the characters to uppercase.

* ### Lowercase
The upper() method on a string converts all of the characters to lowercase.
  
## Python Trim String

* ### Right Strip | rstrip()
The rstrip() method used to remove white spaces from “right” side of the string.

* ### Left Strip | lstrip()
The lstrip() method used to remove white spaces from “left” side of the string.

* ### Strip | strip()
The strip() method used to remove any leading and trailing whitespaces including tabs (\t).
  
## Startswith
The startswith() method returns True if the string starts with the specified value, otherwise False.

## Endswith
The startswith() method returns True if the string ends with the specified value, otherwise False.
  
  ## Strings Checking
* ### isupper()
This method returns True if all characters in the string are uppercase, otherwise, returns “False”. 

* It does not take any arguments
* If there is only whitespace in the string then returns “False”, otherwise it's "True"
* If the string contains only digits and numbers then returns “False”, otherwise it's "True"

* ### islower()
This method returns True if all characters in the string are lowercase, otherwise, returns “False”. 

* It does not take any arguments
* If there is only whitespace in the string then returns “False”, otherwise it's "True"
* If the string contains only digits and numbers then returns “False”, otherwise it's "True"

* ### isalpha()
The isalpha() method returns True if all the characters are alphabet letters (a-z).

* ### isalnum()
The isalnum() method returns True if all the characters are alphabet letters (a-z).

* ### isdecimal()
The isdecimal() method returns True if all characters in a string are decimal characters. If not, it returns False.

* ### isspace()
The isspace() method returns True if all the characters in a string are whitespaces, otherwise False.

* ### istitle()
The istitle() method returns True if all words in a text start with a upper case letter, AND the rest of the word are lower case letters, otherwise False.
  
  
