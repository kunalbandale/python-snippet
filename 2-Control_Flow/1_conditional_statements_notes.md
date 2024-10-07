# Python Conditional Statements

Conditional statements in Python allow you to execute different blocks of code based on whether certain conditions are true or false. They are fundamental to controlling the flow of your program.

## 1. if Statement

The `if` statement is used to execute a block of code only if a specified condition is true.

### Syntax:
```python
if condition:
    # code to execute if condition is true
```

### Example:
```python
age = 20

if age >= 18:
    print("You are allowed to vote!")
```

## 2. if-else Statement

The `else` statement is used in conjunction with `if` to execute a block of code when the `if` condition is false.

### Syntax:
```python
if condition:
    # code to execute if condition is true
else:
    # code to execute if condition is false
```

### Example:
```python
age = 16

if age >= 18:
    print("You can Vote!")
else:
    print("You Cannot Vote!")
```

## 3. if-elif-else Statement

The `elif` (short for "else if") statement allows you to check multiple conditions. It comes after an `if` statement and before an optional `else` statement.

### Syntax:
```python
if condition1:
    # code to execute if condition1 is true
elif condition2:
    # code to execute if condition2 is true
else:
    # code to execute if all conditions are false
```

### Example:
```python
age = 20

if age < 13:
    print("You are a Child")
elif age < 18:
    print("You are a teenager")
else:
    print("You are an Adult!")
```

## 4. Nested Conditional Statements

You can place conditional statements inside other conditional statements. This is called nesting.

### Example:
```python
num = int(input("Enter the number: "))

if num >= 0:
    print("The number is positive")
    if num % 2 == 0:
        print("The number is even")
    else:
        print("The number is odd")
else:
    print("The number is zero or negative")
```

## 5. Practical Example: Leap Year Checker

This example uses nested conditional statements to determine if a given year is a leap year.

```python
year = int(input("Enter the year (YYYY): "))

if (year % 4 == 0):
    if (year % 100 == 0):
        if (year % 400 == 0):
            print(year, "is a leap year")
        else:
            print(year, "is not a leap year")
    else:
        print(year, "is a leap year")
else:
    print(year, "is not a leap year")
```

This script checks the following rules for leap years:
1. If a year is divisible by 4, it might be a leap year.
2. If it's also divisible by 100, it might not be a leap year.
3. But if it's divisible by 400, it is a leap year.

These conditional statements allow you to create complex decision-making processes in your Python programs, enabling your code to respond differently based on various conditions and user inputs.