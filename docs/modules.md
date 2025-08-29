# **Python Modules**

## **What is a Module?**

A **module** in Python is a file that contains Python code (functions,
classes, and variables) that you can reuse in other programs.
Modules help you organize your code into logical sections and avoid
repeating yourself.

There are two types of modules:  
1. **Built-in modules** -- come with Python (e.g., `os`, `io`, `math`).  
2. **User-defined modules** -- created by you in separate `.py` files.

You use the `import` statement to load a module into your program.

---

## **Importing a Module**

```python
import math

print(math.sqrt(16))  # 4.0
print(math.pi)        # 3.141592653589793
```

You can also import specific functions:

```python
from math import sqrt, pi

print(sqrt(25))  # 5.0
print(pi)        # 3.141592653589793
```

---

## **Example 1: The `os` Module**

The **`os` module** provides functions to interact with the operating
system (files, directories, environment variables).

```python
import os

# Check if a file exists
if os.path.exists("example.txt"):
    print("File already exists!")
else:
    print("File does not exist yet.")
```
This helps you safely check before creating, reading, or writing files.

---

## **Example 2: The `io` Module**

The **`io` module** provides tools for handling input and output
(working with files in text and binary modes).

```python
import io

# Write text to a file
f = io.open("example_io.txt", "w", encoding="utf-8")
f.write("Hello, this is written using the io module.")
f.close()

# Read the text back
f = io.open("example_io.txt", "r", encoding="utf-8")
content = f.read()
print(content)  # "Hello, this is written using the io module."
f.close()
```

---

## **Why Use Modules?**

- **Organization** → Keeps code clean and modular.  
- **Reusability** → Functions can be used in multiple programs.  
- **Built-in Power** → Python modules provide ready-to-use functionality.  

---

## **More Resources**

- [Python Modules Documentation](https://docs.python.org/3/tutorial/modules.html)  
- [Python OS Module](https://docs.python.org/3/library/os.html)  
- [Python IO Module](https://docs.python.org/3/library/io.html)  

---

## **Summary**

- Modules are reusable pieces of Python code.  
- Use `import` to load built-in or custom modules.  
- `os` is used for file and system operations (like checking if a file exists).  
- `io` is used for reading and writing to files.  

Modules not only help with organization but also enable **reusability**—you can write code once and use it across many projects.
