# Branching


#### Introduction
As of now, the code that we have written has been executed in order, which is always called sequential structure. However, it cannot solve all the problems. For example, when you want to add conditions to an execution, problem arises. Therefore, conditions are very important in function executions.

#### If statements
In Python, a lot of conditions are constructed with "if", "elif"(else if) and "else". I will explain with some examples below:

1. 
```
user = input('Please enter your name')
if user == "Edwin":
	print('This is the user')
else:
	print('This is not the user')
```
Explanation:
In the example above, the program takes in command line input. When the command line input is Edwin, it will display 'This is the user', if not, it will print 'This is not the user'.



2. 
```
x = int(input('Please enter value of x'))
if x > 1:
	print('x is larger than 1')
elif x == 1:
	print ('x is equal to  1')
else:
	print ('x is smaller than 1')
```
Explanation:
In the example above, the program takes in command line input and store it in the variable x. If x is larger than 1, it will print 'x is larger than 1', if it is equal to 1, it will print ' x is equal to 1'. If it is smaller than 1, it will print 'x is smaller than 1'

#### Practice:
1. Write a program which turns scores into grades:
A range: 90+
B range: 80 - 90 ( not including 90)
C range: 70 - 80 ( not including 80)
D range: 60 - 70 ( not including 70)
E range: all scores below 60 (not including 60)

Answer will be in score.py in code file and can be executed with the following command:
``` python3 score.py```


