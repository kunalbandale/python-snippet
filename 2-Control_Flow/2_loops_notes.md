# Python Loops

## Types of Loops
1. For Loop
2. While Loop

## For Loop
- Used for iterating over a sequence (list, tuple, string) or range
- Syntax: `for item in sequence:`

### Iterating over a range
```python
for i in range(1, 6):
    print(i)
# Output: 1, 2, 3, 4, 5

# With step
for i in range(1, 10, 2):
    print(i)
# Output: 1, 3, 5, 7, 9

# Reverse order
for i in range(10, 1, -2):
    print(i)
# Output: 10, 8, 6, 4, 2
```

### Iterating over a string
```python
str = "Kunal"
for char in str:
    print(char)
# Output: K, u, n, a, l
```

## While Loop
- Executes as long as a condition is true
- Syntax: `while condition:`

Example:
```python
count = 0
while count < 5:
    print(count)
    count += 1
# Output: 0, 1, 2, 3, 4
```

## Loop Control Statements

### 1. Break
- Exits the loop prematurely
```python
for i in range(10):
    if i == 5:
        break
    print(i)
# Output: 0, 1, 2, 3, 4
```

### 2. Continue
- Skips the current iteration and continues with the next
```python
for i in range(10):
    if i == 5:
        continue
    print(i)
# Output: 0, 1, 2, 3, 4, 6, 7, 8, 9
```

### 3. Pass
- Null operation (does nothing)
```python
def Hello():
    pass
```

## Nested Loops
- A loop inside another loop
```python
for i in range(3):
    for j in range(2):
        print(f"{i} and {j}")
```

## Examples

### Sum of First n Natural Numbers
Using while loop:
```python
n = 10
sum = 0
count = 1
while count <= n:
    sum += count
    count += 1
print(sum)  # Output: 55
```

Using for loop:
```python
n = 10
sum = 0
for i in range(11):
    sum += i
print(sum)  # Output: 55
```

### Prime Numbers between 1 and 100
```python
for num in range(1, 101):
    if num > 1:
        for i in range(2, num):
            if num % i == 0:
                break
        else:
            print(num)
# Output: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97
```