
# Commonly Used Python Functions

Python includes many built-in functions that make coding easier. Here's a list of some of the most useful functions for beginners, with examples of how to use them.

---

## 1. `print()`

Displays output to the screen.

```python
print("Hello, world!")
```

---

## 2. `len()`

Returns the number of items in a string, list, tuple, or other collection.

```python
name = "Python"
print(len(name))  # Output: 6
```

---

## 3. `type()`

Returns the type of a variable or value.

```python
x = 10
print(type(x))  # Output: <class 'int'>
```

---

## 4. `input()`

Takes input from the user as a string.

```python
name = input("Enter your name: ")
print("Hello, " + name)
```

---

## 5. `int()`, `float()`, `str()`

Convert values between different types.

```python
num_str = "42"
num = int(num_str)     # Converts to integer
pi = float("3.14")     # Converts to float
score = str(99)        # Converts to string
```

---

## 6. `max()` and `min()`

Returns the largest or smallest item from a list or set of values.

```python
numbers = [3, 7, 2, 9]
print(max(numbers))  # Output: 9
print(min(numbers))  # Output: 2
```

---

## 7. `sum()`

Returns the total of all values in a list.

```python
scores = [10, 20, 30]
print(sum(scores))  # Output: 60
```

---

## 8. `range()`

Generates a sequence of numbers. Commonly used in loops.

```python
for i in range(5):
    print(i)
# Output: 0 1 2 3 4
```

---

## 9. `round()`

Rounds a float to the nearest integer or to a given number of decimal places.

```python
print(round(3.14159))      # Output: 3
print(round(3.14159, 2))   # Output: 3.14
```

---

## 10. `sorted()`

Returns a new sorted list from the items in an iterable.

```python
numbers = [5, 3, 8, 1]
print(sorted(numbers))  # Output: [1, 3, 5, 8]
```

---

## Summary Table

| Function    | Description                              |
|-------------|------------------------------------------|
| `print()`   | Display output                           |
| `len()`     | Get length of a string or collection     |
| `type()`    | Check data type                          |
| `input()`   | Take user input                          |
| `int()`, `float()`, `str()` | Convert between types     |
| `max()`, `min()` | Get max/min value                   |
| `sum()`     | Add all items in a list                  |
| `range()`   | Generate a sequence of numbers           |
| `round()`   | Round numbers                            |
| `sorted()`  | Sort a list or iterable                  |

These functions form a solid foundation for writing basic Python programs. Practice using them often!
