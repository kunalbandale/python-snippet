# Python Variables: Comprehensive Notes

## Introduction to Variables
A variable in Python is a named location in memory that stores a value. It acts as a container for data, allowing you to store and manipulate information in your program.

## Topics Covered
1. Intro to variables
2. Declaring and Assigning Variables
3. Naming Conventions
4. Understanding Variable Types
5. Type Checking and Conversion
6. Dynamic Typing
7. Taking User Input
8. Simple Calculator Application

## Declaring and Assigning Variables
In Python, you can declare and assign variables in a single step:

```python
age = 32
height = 6.1
name = "Kunal"
is_student = True
```

To print variable values:
```python
print("age:", age)
print(height)
print(is_student)
```

## Naming Conventions
- Variable names should be descriptive
- They must always start with a letter or underscore
- Variable names are case-sensitive

Valid examples:
```python
first_name = "Kunal"
last_name = "Bandale"
```

Invalid examples:
```python
# 3hello = 34  # Can't start with a number
# -func = 3    # Can't start with a symbol
# @name = 'hello'  # Can't use special characters
```

## Understanding Variable Types
Python is dynamically typed, meaning the type of a variable is determined at runtime:

```python
age = 32        # integer
height = 6.1    # float
name = "Kunal"  # string
is_student = True  # boolean
```

To check the type of a variable:
```python
print(type(is_student))  # Output: <class 'bool'>
```

## Type Checking and Conversion
You can convert between data types:

```python
age_str = str(age)
print(type(age_str))  # Output: <class 'str'>
```

## Dynamic Typing
Python allows the type of a variable to change as the program executes:

```python
var = 10
print(var, type(var))  # Output: 10 <class 'int'>

var = "Hello"
print(var, type(var))  # Output: Hello <class 'str'>

var = 5.5
print(var, type(var))  # Output: 5.5 <class 'float'>
```

## Taking User Input
Use the `input()` function to get user input. Note that `input()` always returns a string, so you may need to convert it:

```python
age = int(input("Enter Your Age:"))
print(age)
```

## Simple Calculator Application
Here's an example of a simple calculator using variables and user input:

```python
num1 = float(input("Enter first Number:"))
num2 = float(input("Enter second Number:"))

sum = num1 + num2
difference = num1 - num2
product = num1 * num2
quotient = num1 / num2

print(sum)
print(difference)
print(product)
print(quotient)
```

This calculator takes two numbers as input and performs addition, subtraction, multiplication, and division operations.