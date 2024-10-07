# Python Sets

## Introduction
- Sets are built-in data types in Python for storing collections of unique items
- Characteristics:
  - Unordered (elements don't follow a specific order)
  - No duplicate elements
  - Useful for membership tests, eliminating duplicates, and set operations

## Creating Sets
```python
# Using curly braces
set_one = {1, 2, 3, 4, 5}

# Using set() constructor
empty_set = set()
list_to_set = set([1, 2, 3, 4])
tuple_to_set = set((1, 2, 3, 4, 5, 6))
```

## Basic Set Operations
```python
# Adding elements
my_set.add(10)

# Removing elements
my_set.remove(3)  # Raises error if not found
my_set.discard(11)  # No error if not found

# Popping an element
removed_element = my_set.pop()

# Clearing all elements
my_set.clear()
```

## Set Membership Test
```python
3 in my_set  # Returns True or False
```

## Mathematical Set Operations
```python
# Union
union_set = set1.union(set2)

# Intersection
intersection_set = set1.intersection(set2)
set1.intersection_update(set2)

# Difference
diff_set = set1.difference(set2)

# Symmetric Difference
sym_diff = set1.symmetric_difference(set2)
```

## Additional Set Methods
```python
# Subset check
set1.issubset(set2)

# Superset check
set1.issuperset(set2)
```

## Use Cases
- Removing duplicates from a collection
- Membership testing
- Mathematical set operations in various algorithms