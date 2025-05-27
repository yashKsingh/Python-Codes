# Python-Codes
Python Codes from basics

## 1. Syntax and Semantics

**Question 1:** Write a Python program to print "Hello, World!".
# Solution
print("Hello World")

**Question 2:** Write a Python program that takes a user input and prints it.
# Solution
user = input("Please enter something: ")
print(f"You entered: {user}")

**Question 3:** Write a Python program to check if a number is positive, negative, or zero.
# Solution

number= float(input("Enter uour mumber:  "))
if number > 0:
    print("Positive")
elif number== 0:
    print("Zero")
else:
    print("Negative")
    
**Question 4:** Write a Python program to find the largest of three numbers.
# Solution

num1= int(input("Please enter something: "))
num2= int(input("Please enter something: "))
num3= int(input("Please enter something: "))
if num1 > num2 and num1 > num3:
    print("The largest number is: ", num1)
elif num2 > num1 and num2 > num3:
    print("The largest number is: ", num2)
else: 
    largest = num3
    print("The largest number is: ", num3)
    
**Question 5:** Write a Python program to calculate the factorial of a number.
# Solution

def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)
    
num = int(input("Enter a number: "))
print(f"The factorial of {num} is {factorial(num)}")

## 2. Variables and Data Types

**Question 6:** Create variables of different data types: integer, float, string, and boolean. Print their values and types.
# Solution
integer_var = 10
float_var = 10.5
string_var = "Hello"
boolean_var = True

print(f"Integer value: {integer_var}, type: {type(integer_var)}")
print(f"Float value: {float_var}, type: {type(float_var)}")
print(f"String value: {string_var}, type: {type(string_var)}")
print(f"Boolean value: {boolean_var}, type: {type(boolean_var)}")

**Question 7:** Write a Python program to swap the values of two variables.
# Solution
a = 5
b = 10
print(f"Before swap: a = {a}, b = {b}")

# Swapping
a, b = b, a
print(f"After swap: a = {a}, b = {b}")

**Question 8:** Write a Python program to convert Celsius to Fahrenheit.
# Solution
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print(f"{celsius}°C is equal to {fahrenheit}°F")

**Question 9:** Write a Python program to concatenate two strings.
# Solution
string1 = input("Enter first string: ")
string2 = input("Enter second string: ")
concatenate_string = string1 + ""+string2
print(f"Concatenated string: {concatenate_string}")

**Question 10:** Write a Python program to check if a variable is of a specific data type.
# Solution
var= 11.4
if isinstance(var, float):
    print (f" {var} is a float")
else:
    print (f" {var} is not a float")

## 3. Basic Operators (Arithmetic, Comparison, Logical)

**Question 11:** Write a Python program to perform arithmetic operations: addition, subtraction, multiplication, and division.
# Solution
a= 5
b= 4
print(f"Addition: {a} + {b} = {a + b}")
print(f"Subtraction: {a} - {b} = {a - b}")
print(f"Multiplication: {a} * {b} = {a * b}")
print(f"Division: {a} / {b} = {a / b}")

**Question 12:** Write a Python program to demonstrate comparison operators: equal to, not equal to, greater than, less than.
# Solution
a = 5
b = 3

print(f"{a} == {b}: {a == b}")
print(f"{a} != {b}: {a != b}")
print(f"{a} > {b}: {a > b}")
print(f"{a} < {b}: {a < b}")
                
**Question 13:** Write a Python program to demonstrate logical operators: and, or, not.
# Solution
a = True
b = False

print(f"True and False: {a and b}")
print(f"True or False: {a or b}")
print(f"not True: {not a}")

**Question 14:** Write a Python program to calculate the square of a number.
# Solution
num = float(input("Enter a number: "))
square = num ** 2
print(f"The square of {num} is {square}")

**Question 15:** Write a Python program to check if a number is even or odd.
# Solution
num = int(input("Enter a number: "))
if num % 2 == 0:
    print(f"{num} is even")
else:
    print(f"{num} is odd")
    
**Question 16:** Write a Python program to find the sum of the first n natural numbers.
# Solution
n= int(input("Enter a number: "))
sum_n= ( n* (n+1)) // 2
print(f"The sum of first {n} natural numbers is: {sum_n}")

**Question 17:** Write a Python program to check if a year is a leap year.
# Solution
year = int(input("Enter a year: "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")
    
**Question 18:** Write a Python program to reverse a string.
# Solution
string = input("Enter a string: ")
reversed_string = string[::-1]
print(f"The reversed string is: {reversed_string}")

**Question 19:** Write a Python program to check if a string is a palindrome.
# Solution
string = input("Enter a string: ")
if string == string[::-1]:
    print(f"{string} is a palindrome.")
else:
    print(f"{string} is not a palindrome.")
    
