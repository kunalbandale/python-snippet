# Python Operators

## Introduction
Operators in Python are special symbols or keywords that perform operations on variables and values. Python supports various types of operators, including arithmetic, comparison, and logical operators.

## 1. Arithmetic Operators
Arithmetic operators are used to perform mathematical operations.

### 1.1 Addition (+)
- Symbol: `+`
- Example: `a + b`
- Result: Sum of `a` and `b`

### 1.2 Subtraction (-)
- Symbol: `-`
- Example: `a - b`
- Result: Difference between `a` and `b`

### 1.3 Multiplication (*)
- Symbol: `*`
- Example: `a * b`
- Result: Product of `a` and `b`

### 1.4 Division (/)
- Symbol: `/`
- Example: `a / b`
- Result: Quotient of `a` divided by `b` (float)

### 1.5 Floor Division (//)
- Symbol: `//`
- Example: `a // b`
- Result: Quotient of `a` divided by `b`, rounded down to the nearest integer

### 1.6 Modulus (%)
- Symbol: `%`
- Example: `a % b`
- Result: Remainder of `a` divided by `b`

### 1.7 Exponentiation (**)
- Symbol: `**`
- Example: `a ** b`
- Result: `a` raised to the power of `b`

### Example:
```python
a = 10
b = 5

print(a + b)   # 15
print(a - b)   # 5
print(a * b)   # 50
print(a / b)   # 2.0
print(a // b)  # 2
print(a % b)   # 0
print(a ** b)  # 100000
```

## 2. Comparison Operators
Comparison operators are used to compare values. They return boolean results (True or False).

### 2.1 Equal to (==)
- Symbol: `==`
- Example: `a == b`
- Result: True if `a` is equal to `b`, False otherwise

### 2.2 Not equal to (!=)
- Symbol: `!=`
- Example: `a != b`
- Result: True if `a` is not equal to `b`, False otherwise

### 2.3 Greater than (>)
- Symbol: `>`
- Example: `a > b`
- Result: True if `a` is greater than `b`, False otherwise

### 2.4 Less than (<)
- Symbol: `<`
- Example: `a < b`
- Result: True if `a` is less than `b`, False otherwise

### 2.5 Greater than or equal to (>=)
- Symbol: `>=`
- Example: `a >= b`
- Result: True if `a` is greater than or equal to `b`, False otherwise

### 2.6 Less than or equal to (<=)
- Symbol: `<=`
- Example: `a <= b`
- Result: True if `a` is less than or equal to `b`, False otherwise

### Example:
```python
a = 10
b = 20
str1 = 'Kunal'
str2 = 'kunal'

print(a == b)  # False
print(str1 != str2)  # True
print(a > b)  # False
print(a < b)  # True
```

## 3. Logical Operators
Logical operators are used to combine conditional statements.

### 3.1 AND
- Keyword: `and`
- Returns True if both statements are true

### 3.2 OR
- Keyword: `or`
- Returns True if at least one of the statements is true

### 3.3 NOT
- Keyword: `not`
- Reverses the result, returns False if the result is true

### Example:
```python
x = True
y = False

print(x and y)  # False
print(x or y)   # True
print(not x)    # False
```

These operators are fundamental to Python programming and are used extensively in control flow, conditional statements, and data manipulation.