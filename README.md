100+ Python challenging programming exercises

1.	Level description
Level	Description
Level 1	Beginner means someone who has just gone through an introductory Python course. He can solve some problems with 1 or 2 Python classes or functions. Normally, the answers could directly be found in the textbooks.
Level 2	Intermediate means someone who has just learned Python, but already has a relatively strong programming background from before. He should be able to solve problems which may involve 3 or 3 Python classes or functions. The answers cannot be directly be found in the textbooks.
Level 3	Advanced. He should use Python to solve more complex problem using more rich libraries functions and data structures and algorithms. He is supposed to solve the problem using several Python standard packages and advanced techniques.

2.	Problem template

#----------------------------------------#
Question
Hints
Solution

3.	Questions

#----------------------------------------#
Question 1
Level 1(Functions with Arguments)

Question:
WAP to check whether a program is even or not ?

Hints: Use mod to check

solution:

num = int(input("Enter the number you want to check -> "))

def even(num):
    if num % 2 == 0:
        print(f"{num} is an even number")
    else:
        print(f"{num} is not an even number")
        
even(num)        

#......................................................#

#......................................................#

Question 2
Level 1 (Function with Argument)

Question:
WAP to check a number is odd or not

Hints: use mod

Solution:

num = int(input("Enter a number to check whether it is odd or not -> "))

def odd(num):
    if num % 2 != 0:
        print(f"{num} is an odd number")
    else:
        print(f"{num} is not an odd number")
        
odd(num)    

#.................................................#

#.................................................#

Question 3
Level 1  (Function with Argument)

Question:
WAP to find a factorial of a number

Hints: use a loop

Solution:

num = int(input("Enter a number to find out its factorial -> "))

def factorial(num):
    fact = 1
    while num > 0:
        fact *= num
        num -= 1
    print(f"Factorial of {num} is {fact}")    

factorial(num)        

#..............................................#

#..............................................#

Question 4
Level 1(Function using Argument)

Question:
WAP to print a table of a number

Hint: Using a loop

Solution:

num1 = int(input("Enter the number whose table you want to print -> "))
num2 = int(input("Enter upto which number you want the multiplication -> "))

def table(num1, num2):
    for i in range(1, num2 + 1, 1):
        print(f"{num1} * {i} = {num1 * i}")
        
table(num1, num2)        

#...........................................#

#...........................................#

Question 5
Level 1(Function with Argument)

Question:
WAP to find a x to the power of n

Hint: Use Loop

Solution:

x = int(input("Enter the base number -> "))
n = int(input("Enter the power which you want to raise to the base -> "))

def power_of(x, n):
    power = 1
    for i in range(n):
        power *= x
    print(f"{x} to the power of {n} is {power}")    

power_of(x,n)
