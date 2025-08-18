# Python Dictionary Data Type

## What is a Dictionary?

A **dictionary** in Python is a collection of key-value pairs.
Each key must be unique, and it maps to a value.

Dictionaries are useful for storing data that is best represented as a
mapping (like a real dictionary with words and definitions).

Examples:

``` python
student = {
    "name": "Alice",
    "age": 20,
    "grade": "A"
}
```

------------------------------------------------------------------------

## Creating Dictionaries

``` python
empty_dict = {}
person = {"name": "Bob", "age": 25}
```

You can also use the `dict()` function:

``` python
person = dict(name="Charlie", age=30)
```

------------------------------------------------------------------------

## Accessing Values

You can access values by their keys:

``` python
student = {"name": "Alice", "age": 20}
print(student["name"])  # "Alice"
print(student.get("age"))  # 20
```

If a key is missing, `get()` returns `None` (or a default value you
specify):

``` python
print(student.get("grade", "Not Assigned"))  # "Not Assigned"
```

------------------------------------------------------------------------

## Modifying Dictionaries

``` python
student = {"name": "Alice", "age": 20}

# Add new key-value pair
student["grade"] = "A"

# Update value
student["age"] = 21

print(student)  # {'name': 'Alice', 'age': 21, 'grade': 'A'}
```

------------------------------------------------------------------------

## Removing Items

``` python
student = {"name": "Alice", "age": 20, "grade": "A"}

student.pop("grade")     # Removes 'grade'
del student["age"]       # Removes 'age'
student.clear()          # Removes everything

print(student)  # {}
```

------------------------------------------------------------------------

## Looping Through Dictionaries

``` python
student = {"name": "Alice", "age": 20, "grade": "A"}

# Loop over keys
for key in student:
    print(key)

# Loop over values
for value in student.values():
    print(value)

# Loop over key-value pairs
for key, value in student.items():
    print(key, "→", value)
```

Output:

    name → Alice
    age → 20
    grade → A

------------------------------------------------------------------------

## Useful Dictionary Methods

``` python
student = {"name": "Alice", "age": 20}

print(student.keys())    # dict_keys(['name', 'age'])
print(student.values())  # dict_values(['Alice', 20])
print(student.items())   # dict_items([('name', 'Alice'), ('age', 20)])

# Update dictionary
student.update({"grade": "A", "age": 21})
print(student)  # {'name': 'Alice', 'age': 21, 'grade': 'A'}
```

------------------------------------------------------------------------

## Nested Dictionaries

Dictionaries can hold other dictionaries:

``` python
school = {
    "student1": {"name": "Alice", "age": 20},
    "student2": {"name": "Bob", "age": 22}
}

print(school["student1"]["name"])  # "Alice"
```

------------------------------------------------------------------------

## Summary

-   **Dictionaries** store key-value pairs.
-   Keys must be unique and immutable (strings, numbers, tuples).
-   Values can be any data type.
-   Support operations like adding, updating, removing, and looping.
-   Great for structured data like records or JSON.

Dictionaries are one of the most powerful and flexible data types in
Python!
