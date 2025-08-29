
# **Python Conditionals**

Conditionals in Python allow you to make decisions in your code. They let your program behave differently based on different inputs or states.

---

## **The `if` Statement**

The most basic conditional is the `if` statement. It runs a block of code only if the condition is `True`.

```python
age = 18

if age >= 18:
    print("You are an adult.")
```

---

## `if`...`else` Statement

Use `else` to provide an alternative block of code when the condition is `False`.

```python
age = 16

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

---

## **Comparison Operators**

These are used to compare values and return a boolean (`True` or `False`).

| Operator | Meaning            | Example       | Result  |
|----------|--------------------|---------------|---------|
| `==`     | Equal to           | `5 == 5`      | `True`  |
| `!=`     | Not equal to       | `5 != 3`      | `True`  |
| `>`      | Greater than       | `7 > 3`       | `True`  |
| `<`      | Less than          | `2 < 1`       | `False` |
| `>=`     | Greater or equal   | `3 >= 3`      | `True`  |
| `<=`     | Less or equal      | `2 <= 5`      | `True`  |

### **Examples in Conditionals:**

```python
a = 10
b = 20

# Check for equality
if a == b:
    print("a and b are equal")
else:
    print("a and b are not equal")

# Check for ordering
if a < b:
    print("a is less than b")

# Combine comparison and action
if b >= 20:
    print("b is at least 20")
```

---

## **Logical Operators**

Logical operators combine multiple conditions into a single boolean result.

| Operator | Description       | Example                         | Result  |
|----------|-------------------|---------------------------------|---------|
| `and`    | Both must be true | `(5 > 2 and 3 < 4)`             | `True`  |
| `or`     | At least one true | `(5 < 2 or 3 < 4)`              | `True`  |
| `not`    | Reverses boolean  | `not (5 == 5)`                  | `False` |

### **Examples in Conditionals:**

```python
x = 7

# Using 'and'
if x > 5 and x < 10:
    print("x is between 5 and 10")

is_weekend = True
is_holiday = False

# Using 'or'
if is_weekend or is_holiday:
    print("You can relax today")

logged_in = False

# Using 'not'
if not logged_in:
    print("Please log in")
```

---

## **Nested Conditionals**

You can put `if` statements inside other `if` statements.

```python
x = 15

if x > 10:
    if x < 20:
        print("x is between 10 and 20")
```

---

## `if`...`elif`...`else` Statement

Use `elif` (short for "else if") to check multiple conditions in order.

```python
score = 75

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Grade: D or F")
```

---

## **Summary**

- Use `if`, `elif`, and `else` to control the flow of your program.
- Use comparison operators to evaluate values inside conditionals.
- Use logical operators to combine multiple conditions inside `if` statements.
- Nest conditionals for more complex decision trees.

Conditionals make Python programs flexible and interactive.
