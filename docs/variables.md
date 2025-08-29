# **Python Variables**

Variables are one of the most fundamental concepts in Python programming. They are used to store data that can be used and changed throughout your program.

## **What is a Variable?**

A variable is a name that refers to a value. Think of it as a labeled box where you can store information to use later.

```python
age = 25
name = "Alice"
temperature = 36.6
```

In the examples above:
- `age` is storing an integer.
- `name` is storing a string.
- `temperature` is storing a float (decimal number).

## **Rules for Naming Variables**

Python has a few rules and guidelines for naming variables:

- Must start with a letter (a–z, A–Z) or an underscore `_`.
- Can only contain letters, numbers, and underscores.
- Cannot use Python keywords like `if`, `class`, or `while`.
- Variable names are case-sensitive (`Name` and `name` are different).

**Valid examples:**

```python
student_name = "Bob"
_age = 30
total3 = 45
```

**Invalid examples:**

```python
3total = 100       # Starts with a number
class = "Math"     # 'class' is a reserved keyword
student-name = "Sam"  # Contains a hyphen
```

## **Data Types**

Variables can hold different types of data. Some common ones are:

| Type        | Example              |
|-------------|----------------------|
| Integer     | `x = 10`             |
| Float       | `pi = 3.14`          |
| String      | `name = "Charlie"`   |
| Boolean     | `is_sunny = True`    |
| List        | `fruits = ["apple", "banana"]` |
| Dictionary  | `student = {"name": "Anna", "age": 21}` |

Python automatically detects the type of data you assign to a variable.

## **Changing Values**

You can reassign a new value to a variable at any time.

```python
score = 90
score = 95  # score now holds 95
```

## **Multiple Assignments**

Python allows you to assign values to multiple variables in one line.

```python
x, y, z = 1, 2, 3
```

You can also assign the same value to multiple variables:

```python
a = b = c = 0
```

## **Using Variables in Expressions**

Variables can be used in calculations and expressions.

```python
a = 10
b = 5
result = a + b  # result is 15
```

## The `type()` Function

Use `type()` to find out the type of value a variable holds:

```python
x = 5
print(type(x))  # Output: <class 'int'>
```

## **Summary**

- Variables store data values.
- Python automatically infers the type of the variable.
- Follow naming rules for clean, readable code.
- Use variables to hold, update, and manipulate data.
