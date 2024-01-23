### naming conventions
1. PascalCase
2. snake_case (use for python)
3. camelCase

### Syntax - keywords
special keywords in python that *cannot* be used
```import keyword

print(keyword.kwlist)
```
To see list of keywords

### Python literal strings

### Strings
To escape the quotes use \ ...

### Concatenating Python Strings
1) Concatenating literal strings:
		```greeting1 = 'Hello'
		greeting2 = 'FAU'
		print(greeting1 + ' ' + greeting2)```

3) Concatenating strings using the join() method:
		```s1 = 'string'
		s2 = ```


### Accessing string elements
string is a sequence of chars, you can access it's elements using an index.
First char has index of zero.
If you use a negative index, Python returns char starting from end of the string.

```str = "Python String"
   print str[0] = P
   
```
To find the final index of a string:
```
print(str[len(str) - 1])
```
### Slicing Strings
Slicing allows you to get a substring from a string.
The syntax for slicing is as follows:
```
string[start:end]
```
The substring 


### Python Strings are immutable
Python strings are *immutable* meaning you cannot




### Python Data Types

copy chart


### Numbers : integers
in other languages like c# uses 32 bits for integers and 64 bit for float

However, in python it uses a variable num of bits, meaning it is not fixed

### Numbers : float
with floats, python uses a fixed number of bytes


### Constants
**Python doesn't support constants**

To work around this, you use all capital letters to indicate that the variable should be treated as a constant

### Type Conversion
int(str) - convert a string to int num
float(str) - convert a string to floating point num
bool(val) - convert value to boolean value, either **True** or **False**
str(val) -  return the string representation of a value

### Comparison operators
less than( <)


### Logical operators
copy img from powerpoint

### If statement
```
if condition:
	if-block
```

```
age = input('Enter your age')
if int(age) >= 18:
	print("You can vote")
print("go vote")
```

### If else statement



### if elif else statement



### for loop statement with the range()
```
for index in range()
```

### while



### break - for loop
**break** - is used to 


### break - while loop


### continue
the continue statement is used inside a for loop or a while loop. Continue statement skips 


### pass 
is a statement that does nothing. It's just a placeholder for code you'll write in the future.


### Functions
name code black that performs a job or returns a value.

Use functions to divide a large program into smaller and more manageable parts.


```
def greet()
	# display a greeting to users
	print('Hi')
```


### Recursion
process of defining of something in terms of itself.
i.e. function that calls itself

### modules
can be defined as .py a python program file containing functions, classes, or variables. Provides flexibility to organize the code in a logical way.

1.  import statement
2. from import statement

### Packages
facilitate developer with app development environment by providing

### List 


### Tuple
a tuple is a list that cannot change. Python refers to a value that cannot change as immutable. So by definition, a **Tuple is an immutable list.**


### Sorted Function
sort() method sorts a list in place. 



### Set
python set is an unordered list of immutable elements. It means: 
- elements in a set are unordered
- elements in a set are unique. A set doesn't allow duplicate elements.
- elements in a set cannot be changed
To define a set in python


### from white board
               ordered   immutable. unordered-immut
- data types: (list,               tuple,                set,       dictionary)
            [].       ()        {}.       {}




### set operations



### Dictionary

is a collection of key-value pairs where each key is associated with a value.

A value in the key-pair can be a number, strings, list, 


```
empty-dict = {}
```

To access 



### NumPy
stands for **Numerical Python** and is a Python library that performs numerical calculations.

NumPy is very fast b/c it is written in c language.

Built on linear algebra. It's about matrices and vectors and performing mathematical calculations on them.

Unlike built-in list type tha tcan hold the elements of different types.

one data type for all elements. 







The key concept in NumPy is the NumPy array data type. A NumPy array may have one or more dimensions.

Vector (1D array), Matrice (2D array), Tensor (3D array)
see images




### NumPy
```
pip install numpy
```

```
import numpy as np
```





### Getting Shapes

The shape returns a tuple:

- the number of elements in the tuple is the number of axis.
- each tuple element stores the number of elements of the corresponding axis.

look at image slide 93


### NumPy zeros() - ones()

The **zeroes** function

### Arrange()

numPy arrange() 



### Array indexing - 1D
along a single axis, you can select elements using indices




### array slicing 
numPy array use brackets[] and : notations for slicing


### arrray slicing - multidim array



### aggregate functions