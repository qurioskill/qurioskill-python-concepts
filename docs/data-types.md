
# Python Data Types: int, float, str, bool

Python has several built-in data types. This guide focuses on four fundamental types:

- `int` (Integer)
- `float` (Floating-point number)
- `str` (String)
- `bool` (Boolean)

We'll also explore common operators used with each type.

---

## 1. Integer (`int`)

Integers are whole numbers, positive or negative, without decimals.

```python
a = 10
b = -5
```

### Common Operators with Integers

| Operator | Description       | Example     | Result |
|----------|-------------------|-------------|--------|
| `+`      | Addition           | `5 + 3`     | `8`    |
| `-`      | Subtraction        | `5 - 2`     | `3`    |
| `*`      | Multiplication     | `4 * 3`     | `12`   |
| `/`      | Division           | `10 / 2`    | `5.0`  |
| `//`     | Floor Division     | `10 // 3`   | `3`    |
| `%`      | Modulus (remainder)| `10 % 3`    | `1`    |
| `**`     | Exponentiation     | `2 ** 3`    | `8`    |

---

## 2. Float (`float`)

Floats represent real numbers with decimal points.

```python
pi = 3.14159
height = 5.7
```

### Common Operators with Floats

Floats support all the same operators as integers:

| Operator | Description         | Example       | Result     |
|----------|---------------------|---------------|------------|
| `+`      | Addition             | `2.5 + 1.5`   | `4.0`      |
| `-`      | Subtraction          | `5.5 - 2.0`   | `3.5`      |
| `*`      | Multiplication       | `2.0 * 3.5`   | `7.0`      |
| `/`      | Division             | `7.0 / 2.0`   | `3.5`      |
| `//`     | Floor Division       | `7.5 // 2.0`  | `3.0`      |
| `%`      | Modulus              | `7.5 % 2.0`   | `1.5`      |
| `**`     | Exponentiation       | `3.0 ** 2`    | `9.0`      |

---

## 3. String (`str`)

Strings are sequences of characters enclosed in quotes.

```python
name = "Alice"
greeting = 'Hello'
```

### Common Operators with Strings

| Operator | Description                 | Example                    | Result            |
|----------|-----------------------------|----------------------------|-------------------|
| `+`      | Concatenation               | `"Hi " + "there"`          | `"Hi there"`      |
| `*`      | Repetition                  | `"ha" * 3`                 | `"hahaha"`        |
| `in`     | Membership                  | `"a" in "banana"`          | `True`            |
| `not in` | Not membership              | `"z" not in "banana"`      | `True`            |

**String Indexing and Slicing:**

```python
text = "Python"
print(text[0])      # 'P'
print(text[1:4])    # 'yth'
```

---

## 4. Boolean (`bool`)

Booleans represent truth values: `True` or `False`.

```python
is_active = True
is_admin = False
```

### Common Boolean Operators

| Operator | Description         | Example             | Result  |
|----------|---------------------|---------------------|---------|
| `and`    | Logical AND         | `True and False`    | `False` |
| `or`     | Logical OR          | `True or False`     | `True`  |
| `not`    | Logical NOT         | `not True`          | `False` |

### Comparison Operators

These operators return boolean values and are often used with all data types:

| Operator | Description       | Example       | Result  |
|----------|-------------------|---------------|---------|
| `==`     | Equal to          | `5 == 5`      | `True`  |
| `!=`     | Not equal to      | `5 != 3`      | `True`  |
| `>`      | Greater than      | `7 > 3`       | `True`  |
| `<`      | Less than         | `2 < 1`       | `False` |
| `>=`     | Greater or equal  | `3 >= 3`      | `True`  |
| `<=`     | Less or equal     | `2 <= 5`      | `True`  |

---

## Summary

| Data Type | Description                          |
|-----------|--------------------------------------|
| `int`     | Whole numbers                        |
| `float`   | Decimal numbers                      |
| `str`     | Text enclosed in quotes              |
| `bool`    | Logical values: `True` or `False`    |

Understanding these basic types and their operators is essential for writing effective Python code.
