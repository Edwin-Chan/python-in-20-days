# Elements of Python

#### Basic Types in Python
In programming, variables are used to store values. Here are some of the basic types of variables which is oftenly used in Python

1. int : 
Python 3 supports base of 2 (0b100, which is 4), 8 (0o100, which is 64), 10 (100), and 16 (0x100, which is 256).

2. float : 
This type is for values which involve a decimal point. It can support mathematic notation(eg 123.123) and also scientific notations(eg 1.234e2)

3. string: 
String are words which are quoted with single quotes( '' ) and also double quotes (""). It also includes different type of representations, such as raw, Unicode. You can also use triple quotes to keep the formats as listed in the code

Example:
```
>>> str1 = """
... List of name:
... Alice
... Bob
... """

>>> print(str1)
List of name:
Alice 
Bob

```
 
4. Boolean: 
Boolean only has two type of values: True , False. (Remember that both values start with a capital letter.) 
So what is True? For example:
 4 < 5    #True
 1 == 2   #False

5. Complex number (More used in scientific calculations)
It is more often used in like mathematical calculations. For example, in complex numbers it is always represented in x + y i , but in Python mathematical representation, the imaginary part i is replaced by j. For example, if the complex number is 2 + 3i, then the Python equivalent representation is 2 + 3j.

#### Rules on naming variables

For naming variables, it is always advisable to make it clearly understandable and readable. However, there are a few rules to remember:
1. Variables should be formed with characters, numbers and underscores. However, variable name should not start with numbers

2. Variable names are case sensitive ( a and A are two different variables!)

3. Variable names should not have conflict with reserved words and also module names or function names.

4. Avoid using the same names for variables, or else it reduces readability of code. 

In the following, I shall explain how varaibles can be used.
How to use variables to calculate?

```
Author: Edwin Chan

a = 123 
b = 122
print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)

```
#### How to check type of variables?

```
Author: Edwin Chan
a = 4.2
b = 100
c = 2 + 3 j
d = "hello"
e = False
print(type(a)) # <class 'float'>
print(type(b)) # <class 'int'>
print(type(c)) # <class 'complex'>
print(type(d)) # <class 'str'>
print(type(e)) # <class 'bool'>

```

#### Some useful variable types conversion with built-in functions
1. int() converts strings to integers, eg int('123')-> 123
2. float() converts strings to float, eg float('12.333') -> 12.333
3. str() converts values into strings, eg str(123) -> '123'

#### Some useful built-in functions
1. input() is used to get keyboard input
2. print() is used to show the values on terminal

```
a = int(input('please input value of a'))
b = int(input('please input value of b'))
print('the value of a is ' + str(a))
print('the value of b is ' + str(b))

```

#### Practice(Answer can be found in code file)
1. Convert temperature from Fahrenheit scale to Celsius scale, take in the Fahrenheit temperature from keyboard, and print out the answer. (conversion.py)


Answers can be executed with Python3 in the terminal: 
```python3 conversion.py```





