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
