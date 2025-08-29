# **Python List Data Type**

## **What is a List?**

A **list** in Python is an ordered, mutable collection of items.
Lists can store different types of data such as numbers, strings, or
even other lists.

Examples:

``` python
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", 3.14, True]
```

------------------------------------------------------------------------

## **Creating a List**

You can create a list using square brackets `[]`:

``` python
my_list = [10, 20, 30]
empty_list = []
```

------------------------------------------------------------------------

## **Accessing Elements**

Lists are indexed, starting at `0`. You can access elements using their
index:

``` python
animals = ["cat", "dog", "elephant"]

print(animals[0])   # "cat"
print(animals[1])   # "dog"
print(animals[-1])  # "elephant" (last item)
```

------------------------------------------------------------------------

## **Modifying a List**

Lists are **mutable**, meaning you can change their contents:

``` python
colors = ["red", "blue", "green"]
colors[1] = "yellow"
print(colors)  # ["red", "yellow", "green"]
```

------------------------------------------------------------------------

## **Common List Operations**

``` python
nums = [1, 2, 3]

# Add items
nums.append(4)        # [1, 2, 3, 4]
nums.insert(1, 10)    # [1, 10, 2, 3, 4]

# Remove items
nums.remove(10)       # [1, 2, 3, 4]
nums.pop()            # Removes last → [1, 2, 3]

# Length
print(len(nums))      # 3

# Concatenation
print(nums + [4, 5])  # [1, 2, 3, 4, 5]

# Repetition
print(nums * 2)       # [1, 2, 3, 1, 2, 3]
```

------------------------------------------------------------------------

## **Looping Through a List**

``` python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

Output:

    apple
    banana
    cherry

------------------------------------------------------------------------

## **List Slicing**

Lists support slicing just like strings:

``` python
letters = ["a", "b", "c", "d", "e"]
print(letters[1:4])   # ['b', 'c', 'd']
print(letters[:3])    # ['a', 'b', 'c']
print(letters[::2])   # ['a', 'c', 'e']
```

------------------------------------------------------------------------

## **Nested Lists**

Lists can contain other lists:

``` python
matrix = [[1, 2], [3, 4], [5, 6]]
print(matrix[0])     # [1, 2]
print(matrix[1][1])  # 4
```

------------------------------------------------------------------------

## **Useful List Methods**

``` python
numbers = [3, 1, 4, 1, 5]

print(min(numbers))   # 1
print(max(numbers))   # 5
print(sum(numbers))   # 14

numbers.sort()
print(numbers)        # [1, 1, 3, 4, 5]

numbers.reverse()
print(numbers)        # [5, 4, 3, 1, 1]
```

------------------------------------------------------------------------

## **Summary**

-   **Lists** are ordered, mutable collections of items.
-   Support indexing, slicing, and iteration.
-   Can hold different types of data.
-   Provide many built-in methods (`append`, `remove`, `sort`, etc.).

Lists are one of the most versatile and commonly used data types in
Python!
