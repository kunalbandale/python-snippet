# Python Basics: Syntax and Concepts

## 1. Syntax and Semantics
- Syntax: Set of rules for writing code
- Semantics: Meaning or interpretation of the code

## 2. Comments in Python
- Single-line comments: Use `#`
- Multi-line comments: Use triple quotes `'''` or `"""`

## 3. Case Sensitivity
- Python is case-sensitive
- Variables with different cases are treated as distinct

Example:
```python
name = 'kunal'
Name = 'bandale'
# These are two different variables
```

## 4. Indentation
- Indentation defines code blocks and scope
- Crucial for control structures like if statements

Example:
```python
if age > 30:
    print("You Should take LIC")
print("DONE!!")
```

## 5. Line Continuation
- Use backslash `\` for line continuation in long statements

Example:
```python
total = 1+2+3+4+5+5+\
3+4+3
```

## 6. Multiple Statements on a Single Line
- Use semicolons to separate multiple statements

Example:
```python
x=5;y=4;z=x+y
```

## 7. Variable Assignment and Types
- Variables are assigned using `=`
- Python uses dynamic typing
- Common types: int, str, etc.

Example:
```python
age = 23  # int
name = "kunal"  # str
```

## 8. Type Inference
- Python automatically determines the data type of variables
- Type can change if a new value is assigned

Example:
```python
variable = 10  # int
variable = "Kunal"  # str
```

## 9. Checking Variable Types
- Use `type()` function to check the type of a variable

Example:
```python
print(type(age))  # <class 'int'>
print(type(name))  # <class 'str'>
```