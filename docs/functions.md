
# **Python Functions**

Functions are reusable blocks of code that perform a specific task. They help organize code, reduce repetition, and improve readability.

---

## **What is a Function?**

A function is a named sequence of statements that performs a computation. You define a function once and can use it as many times as needed.

### **Defining a Function**

```python
def greet():
    print("Hello, world!")
```

### **Calling a Function**

```python
greet()  # Output: Hello, world!
```

---

## **Why Use Functions?**

- **Reusability**: Write code once and use it multiple times.
- **Organization**: Break programs into smaller, manageable parts.
- **Maintainability**: Easier to debug and update code.
- **Avoid Repetition**: Reduces duplicate code.

---

## **Function with Parameters**

Functions can accept inputs, known as *parameters*.

```python
def greet(name):
    print(f"Hello, {name}!")
```

### **Example:**

```python
greet("Alice")   # Output: Hello, Alice!
greet("Bob")     # Output: Hello, Bob!
```

---

## **Function with Return Value**

Functions can return values using the `return` statement.

```python
def add(a, b):
    return a + b
```

### **Example:**

```python
result = add(3, 4)
print(result)    # Output: 7
```

---

## **Default Parameters**

You can provide default values for parameters.

```python
def greet(name="Guest"):
    print(f"Hello, {name}!")
```

### **Example:**

```python
greet()           # Output: Hello, Guest!
greet("Diana")    # Output: Hello, Diana!
```

---

## **Keyword and Positional Arguments**

Python supports both positional and keyword arguments.

```python
def describe_pet(animal, name):
    print(f"I have a {animal} named {name}.")
```

### **Example:**

```python
describe_pet("dog", "Buddy")                   # Positional
describe_pet(name="Whiskers", animal="cat")    # Keyword
```

---

## **Returning Multiple Values**

Functions can return multiple values as a tuple.

```python
def get_coordinates():
    x = 5
    y = 10
    return x, y

a, b = get_coordinates()
print(a, b)  # Output: 5 10
```

---

## **Scope of Variables**

Variables defined inside a function are **local** to that function.

```python
def example():
    local_var = "I am local"
    print(local_var)

example()
# print(local_var)  # This would raise an error
```

---

## **Summary**

| Feature                | Description                                 |
|------------------------|---------------------------------------------|
| `def` keyword          | Used to define a function                   |
| `return` statement     | Sends a result back to the caller           |
| Parameters             | Input values passed to a function           |
| Default values         | Optional values for parameters              |
| Reusability            | Functions reduce code duplication           |
| Scope                  | Local vs Global variable access             |

Understanding how to write and use functions is crucial for building efficient and modular Python programs.
