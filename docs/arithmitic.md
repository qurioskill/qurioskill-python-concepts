# Python Arithmetic Data Types

Python provides several built-in data types that can be used to
represent numbers and perform arithmetic operations.

------------------------------------------------------------------------

## 1. Integers (`int`)

An **integer** is a whole number without decimals. It can be positive,
negative, or zero.

Examples:

``` python
x = 10
y = -5
z = 0

print(type(x))  # <class 'int'>
```

Python can handle very large integers without any special syntax.

### Integer Operations

``` python
a = 10
b = 3

print(a + b)   # 13
print(a - b)   # 7
print(a * b)   # 30
print(a // b)  # 3 (floor division)
print(a % b)   # 1 (modulus)
print(a ** b)  # 1000 (exponentiation)
```

------------------------------------------------------------------------

## 2. Floating Point Numbers (`float`)

A **float** represents real numbers with a decimal point.

Examples:

``` python
pi = 3.14159
temperature = -7.5
value = 2.0

print(type(pi))  # <class 'float'>
```

### Float Operations

``` python
x = 5.5
y = 2.0

print(x + y)   # 7.5
print(x - y)   # 3.5
print(x * y)   # 11.0
print(x / y)   # 2.75
```

Floats are useful when precision with decimals is required.

------------------------------------------------------------------------

## 3. Complex Numbers (`complex`)

A **complex number** has a real part and an imaginary part, written as
`a + bj`.

Examples:

``` python
c1 = 2 + 3j
c2 = 4 - 5j

print(type(c1))  # <class 'complex'>
```

### Complex Number Operations

``` python
c1 = 2 + 3j
c2 = 1 - 1j

print(c1 + c2)  # (3+2j)
print(c1 - c2)  # (1+4j)
print(c1 * c2)  # (5+1j)
print(c1 / c2)  # (-0.5+2.5j)
```

Python has built-in support for complex arithmetic.

------------------------------------------------------------------------

## 4. Type Conversion Between Number Types

You can convert between integers, floats, and complex numbers using
built-in functions:

``` python
print(int(3.9))       # 3 (decimal truncated)
print(float(7))       # 7.0
print(complex(5))     # (5+0j)
print(complex(2, 3))  # (2+3j)
```

------------------------------------------------------------------------

## Summary

-   **Integers (`int`)**: Whole numbers, positive or negative.
-   **Floats (`float`)**: Numbers with decimals, for precision.
-   **Complex (`complex`)**: Numbers with real and imaginary parts.
-   Python allows arithmetic operations across all numeric types and
    provides automatic type promotion when needed.

These arithmetic data types form the foundation of numerical programming
in Python!
