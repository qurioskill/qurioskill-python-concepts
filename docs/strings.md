# Python String Data Type

## What is a String?

In Python, a **string** is a sequence of characters enclosed in single
quotes (`'`), double quotes (`"`), or triple quotes (`'''` or `"""`).
Strings are used to represent text.

Examples:

``` python
name = "Alice"
greeting = 'Hello'
paragraph = '''This is
a multi-line
string.'''
```

## Creating Strings

You can create strings using quotes:

``` python
str1 = "Python"
str2 = 'Programming'
str3 = """Multi-line
string example."""
```

## String Operations

Python provides many operations with strings:

``` python
a = "Hello"
b = "World"

print(a + " " + b)  # Concatenation → "Hello World"
print(a * 3)        # Repetition → "HelloHelloHello"
print(len(a))       # Length → 5
```

## Indexing and Slicing

Strings are sequences, so you can access parts of them:

``` python
text = "Python"

print(text[0])   # First character → "P"
print(text[-1])  # Last character → "n"
print(text[0:4]) # Slice → "Pyth"
```

## Common String Methods

Python strings have built-in methods:

``` python
msg = "hello world"

print(msg.upper())    # "HELLO WORLD"
print(msg.lower())    # "hello world"
print(msg.title())    # "Hello World"
print(msg.replace("world", "Python"))  # "hello Python"
print(msg.strip())    # Removes whitespace from start and end
```

## Type Conversion

Convert other data types to strings with `str()`:

``` python
num = 42
print(str(num))  # "42"
```

## Summary

-   Strings represent text in Python.
-   Defined using quotes: `' '`, `" "`, `''' '''`, or `""" """`.
-   Support operations like concatenation, repetition, slicing, and many
    methods.
-   Use `str()` to convert other data types to strings.

Strings are extremely powerful for working with text in Python!
