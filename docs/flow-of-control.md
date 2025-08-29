
# **Python Flow of Control**

When you run a Python script, the interpreter follows a predictable flow to execute the code. This document explains **how Python reads a `.py` file**, what happens with **variable assignments**, **function definitions and calls**, and other control structures—all in a beginner‑friendly way.

---

## **1. Starting the Interpreter**

1. **Read the file**: Python reads your script from top to bottom.
2. **Compile to bytecode**: Behind the scenes, each line is translated into an intermediate form called *bytecode*.
3. **Execute**: A component called the **Python Virtual Machine (PVM)** runs the bytecode line by line.

You don’t need to worry about bytecode in day‑to‑day coding—just know it’s the bridge between your source code and the machine doing the work.

---

## **2. Sequential Execution**

By default, Python executes statements **one after another**:

```python
print("Step 1")
print("Step 2")
```

Output:

```
Step 1
Step 2
```

Unless a control structure (like a `function`, `if`, or `loop`) changes the path, Python keeps moving downward.

---

## **3. Variable Assignments**

When Python encounters an assignment:

```python
x = 5
y = x + 3
```

1. **Evaluate the right side** (`x + 3` → `8`).
2. **Bind** the name on the left (`y`) to that result (`8`) in the current *namespace* (a table that maps names to objects).

Key points:

- No need to declare types—Python figures it out at runtime.
- Reassigning a variable simply points the name to a new object.

---

## **4. Function Definitions (`def`)**

Meeting a `def` statement is *not* a function call. Instead, Python:

1. Creates a **function object** containing the code block.
2. Binds the function’s name to that object.

```python
def greet(name):
    print("Hello,", name)

# No output yet; only definition happened
```

---

## **5. Function Calls**

Calling a function triggers a new *stack frame* (a workspace for that call):

```python
greet("Ada")
```

Steps:

1. **Evaluate arguments** (`"Ada"`).
2. **Push** a new frame with its own local variables.
3. **Execute** the function body line by line.
4. **Return** control (and any value) back to the caller.
5. **Pop** the frame—locals disappear, but any returned value persists.

---

## **6. Control Structures**

### **Conditionals**

```python
if temperature > 30:
    print("Hot!")
else:
    print("Comfortable.")
```

- Python checks the condition top to bottom.
- Executes the first branch that is `True`.

### **Loops**

```python
for i in range(3):
    print(i)
```

- `for` and `while` repeat a block.
- Control returns to the loop header after each iteration until the condition ends.

### `break` and `continue`

- `break` exits a loop early.
- `continue` skips to the next iteration.

---

## **7. Imports**

At an `import` statement, Python:

1. Searches for the module.
2. Executes it **once** (running any top‑level code inside).
3. Adds the module to `sys.modules` cache.
4. Binds the module name (or selected members) in your script.

---

## **8. Putting It All Together — Walk‑Through Example**

```python
# flow_example.py
import math          # Step A

radius = 2           # Step B

def area(r):         # Step C
    return math.pi * r ** 2

print(area(radius))  # Step D
```

| Step | What Happens                                                                 |
|------|------------------------------------------------------------------------------|
| A    | The `math` module is loaded and cached.                                      |
| B    | `radius` is bound to `2`.                                                    |
| C    | Function `area` is created (no calculation yet).                             |
| D    | `area` is **called** → new frame → calculation → control returns with result |

---

## **9. Key Takeaways**

- Python reads your file from **top to bottom**, executing as it goes.
- **Assignments** bind names to objects after evaluating the right side.
- **Function definitions** create objects; **function calls** run them in new frames.
- Control structures (`if`, loops) alter the straight‑line flow.
- Imports run a module’s top‑level code only once, then hand you the module object.

Understanding this flow helps you predict how Python will behave and debug your programs with confidence.
