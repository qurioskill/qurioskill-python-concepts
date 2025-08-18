# Python Modules

## What is a Module?

A **module** in Python is a file that contains Python code (functions,
classes, and variables) that you can reuse in other programs.
Modules help you organize your code into logical sections and avoid
repeating yourself.

There are two types of modules: 1. **Built-in modules** -- come with
Python (e.g., `os`, `io`, `math`). 2. **User-defined modules** --
created by you in separate `.py` files.

You use the `import` statement to load a module into your program.

------------------------------------------------------------------------

## Importing a Module

``` python
import math

print(math.sqrt(16))  # 4.0
print(math.pi)        # 3.141592653589793
```

You can also import specific functions:

``` python
from math import sqrt, pi

print(sqrt(25))  # 5.0
print(pi)        # 3.141592653589793
```

------------------------------------------------------------------------

## Example 1: The `os` Module

The **`os` module** provides functions to interact with the operating
system (files, directories, environment variables).

``` python
import os

# Get current working directory
print(os.getcwd())

# List files in current directory
print(os.listdir())

# Create a new directory
os.mkdir("test_folder")

# Remove a directory
os.rmdir("test_folder")
```

------------------------------------------------------------------------

## Example 2: The `io` Module

The **`io` module** provides tools for handling input and output
(working with files in text and binary modes).

``` python
import io

# Create an in-memory text stream
text_stream = io.StringIO("Hello, Python!")
print(text_stream.read())  # "Hello, Python!"

# Working with file-like binary data
binary_stream = io.BytesIO(b"Python Bytes")
print(binary_stream.read())  # b'Python Bytes'
```

------------------------------------------------------------------------

## Why Use Modules?

-   **Organization** → Keeps code clean and modular.
-   **Reusability** → Functions can be used in multiple programs.
-   **Built-in Power** → Python modules provide ready-to-use
    functionality.

------------------------------------------------------------------------

## More Resources

-   [Python Modules
    Documentation](https://docs.python.org/3/tutorial/modules.html)
-   [Python OS Module](https://docs.python.org/3/library/os.html)
-   [Python IO Module](https://docs.python.org/3/library/io.html)

------------------------------------------------------------------------

## Summary

-   Modules are reusable pieces of Python code.
-   Use `import` to load built-in or custom modules.
-   `os` is used for system operations (directories, files).\
-   `io` is used for handling streams and files.

Modules are one of the most powerful ways to extend Python's
functionality!
