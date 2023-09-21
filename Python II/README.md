# Python-II
## List, Set, and String Operations

## Length
The len() function is used to determine how many items a list, set, and string has.

## Min and Max
* ### Min
If strings are provided as parameters, this function computes the lexicographically lowest value and the minimum of the values sent in as arguments.

* ### Max
If strings are provided as parameters, this function computes the lexicographically highest value and the maximum of the values sent in as arguments.

## Count
The count() method returns the number of elements with the specified value.

## Join
There are several ways to join, or concatenate, two or more lists in Python.
Using the + operator is one of the simplest methods.

## Multiplication
We can multiply lists, sets, and strings using the * operator just like multiplying numbers in general.

## Replication
We can replicate lists, sets, and strings using *, similar to multiplication.

## Range
The range() function returns a sequence of numbers.

* Starting from 0 by default
* Increments by 1 (by default)
* Stops before a specified number [i - 1]

## In
The in operator used to check if an element is found in the iterable. The in operator returns True if an element is found. It returns False if not.

## Not In
The not in operator used to check if an element is not found in the iterable. The in operator returns True if an element is not found. It returns False if found.

## Multiple Variable
Python allows you to assign values to multiple variables in one line.

## Sort
The sort() method sorts the list ascending by default.
You can also make a function to decide the sorting criteria(s).

# Operators, Operands, and Expressions
## Operators
Operators are used to perform operations on variables and values.

### Arithmetic Operators
* \+  :	Addition
* \-  :	Subtraction
* \*  :	Multiplication
* /	  :  Division	
* %	  :  Modulus
* **  : Exponentiation
* //   :	Floor division

### Assignment Operators
* =
* +=
* -=
* *=
* /=
* %=	
* //=
* **= 
* &= 
* |=
* ^=	
* \>>=	
* <<=

### Comparison Operators
* ==	Equal
* !=	Not equal
* \>	Greater than
* <	Less than
* \>=	Greater than or equal to
* <=	Less than or equal to

### Logical Operators
* and : Returns True if both statements are true
* or  :	Returns True if one of the statements is true
* not :	Reverse the result, returns False if the result is true	

### Identity Operators
* is : 	Returns True if both variables are the same object
* is not :	Returns True if both variables are not the same object

### Membership Operators
* in : 	Returns True if a sequence with the specified value is present in the object
* not in :	Returns True if a sequence with the specified value is not present in the object

## Conditional Expressions
These conditions can be used in several ways, most commonly in "if statements" and loops.
* ### If
An "if statement" is written by using the if keyword.
* ### Else
The else keyword catches anything which isn't caught by the preceding conditions.
* ### Elif
The elif keyword is pythons way of saying "if the previous conditions were not true, then try this condition".
* ### Indentation
Python relies on indentation (whitespace at the beginning of a line) to define scope in the code. If statement, without indentation will raise an error.

## For
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
## Nested For
A nested loop is a loop inside a loop.

## While
With the while loop we can execute a set of statements as long as a condition is true.

## Break
With the break statement we can stop the loop even if the while condition is true.

### Continue
Loops iterate over a block of code until the test expression is false, but sometimes we wish to skip the current iteration or even the whole loop without checking test expression.

The continue statement is used to skip the rest of the code inside a loop for the current iteration only. Loop does not terminate but continues on with the next iteration.

the notebook contain examples with different parameters, like:
* Range as parameter
* String as parameter
* List as parameter

### Pass
The pass statement is used as a placeholder for future code.

When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.
Empty code is not allowed in loops, function definitions, class definitions, or in if statements.

### List Comprehension
List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

A Python list comprehension consists of brackets containing the expression, which is executed for each element along with the for loop to iterate over each element in the Python list. 

Advantages of List Comprehension:
* More time-efficient and space-efficient than loops.
* Require fewer lines of code.
* Transforms iterative statement into a formula.

### Syntax Error
A syntax error is an error in the syntax of a coding or programming language, entered by a programmer. 

Syntax errors are caught by a software program called a compiler, and the programmer must fix them before the program is compiled and then run.
Syntax errors is also known as parsing errors.

Syntax error in python shows 2 type of error:
* IndentationError
* SyntaxError

### Exceptions
Even if a statement or expression is syntactically correct, it may cause an error when an attempt is made to execute it. 
Errors detected during execution are called exceptions and are not unconditionally fatal.

Exeption in python shows 3 type of error:
#### NameError
NameErrors are raised when your code refers to a name that does not exist in the current scope.
#### ZeroDivisionError
A ZeroDivisionError is raised when you try to divide by 0. This is part of the ArithmeticError Exception class.
#### TypeError
TypeError is an exception in Python programming language that occurs when the data type of objects in an operation is inappropriate.
