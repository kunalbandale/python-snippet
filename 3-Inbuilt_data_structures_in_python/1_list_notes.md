# Python Lists

## Introduction
- Lists are ordered, mutable collections of items
- They can contain items of different data types

## Contents
1. Creating lists
2. Accessing list elements
3. Modifying list elements
4. List methods
5. Slicing lists
6. Iterating over lists
7. List comprehensions
8. Nested lists

## 1. Creating Lists
```python
empty_list = []
mixed_list = [1, "Hello", True, 1.2]
fruits = ["apple", "banana", "cherry", "kiwi", "orange"]
```

## 2. Accessing List Elements
- Using index: `fruits[0]`  # Returns "apple"
- Negative indexing: `fruits[-1]`  # Returns "orange"

## 3. Modifying List Elements
```python
fruits[1] = "watermelon"
fruits[1:] = ["watermelon"]  # Be careful, this adds each character as an item
```

## 4. List Methods
- `append(item)`: Add an item to the end
- `insert(index, item)`: Add an item at a specific index
- `remove(item)`: Remove the first occurrence of an item
- `pop()`: Remove and return the last item
- `pop(index)`: Remove and return the item at the specified index
- `index(item)`: Get the index of an item
- `count(item)`: Count occurrences of an item
- `sort()`: Sort the list in-place
- `reverse()`: Reverse the list in-place
- `clear()`: Remove all items from the list

## 5. Slicing Lists
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(numbers[2:5])  # [3, 4, 5]
print(numbers[:5])   # [1, 2, 3, 4, 5]
print(numbers[5:])   # [6, 7, 8, 9, 10]
print(numbers[::3])  # [1, 4, 7, 10]
print(numbers[::-1]) # [10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
```

## 6. Iterating Over Lists
```python
for num in numbers:
    print(num)

for index, number in enumerate(numbers):
    print(index, number)
```

## 7. List Comprehensions
Basic syntax: `[expression for item in iterable]`
With conditional logic: `[expression for item in iterable if condition]`
Nested list comprehension: `[exp for item1 in iterable1 for item2 in iterable2]`

Examples:
```python
squares = [x**2 for x in range(10)]
even_numbers = [num for num in range(10) if num % 2 == 0]
pairs = [(i, j) for i in [1, 2, 3, 4] for j in ['a', 'b', 'c', 'd']]
word_lengths = [len(word) for word in ["hello", "world", "python", "list", "comprehension"]]
```

## 8. Nested Lists
Lists can contain other lists, creating multi-dimensional structures.

## Conclusion
Lists are powerful, versatile data structures in Python. List comprehensions provide a concise way to create lists, often replacing more verbose looping constructs. Understanding list operations and comprehensions will help you write cleaner and more efficient Python code.