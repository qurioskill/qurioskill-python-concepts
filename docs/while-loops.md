
# **Python `while` Loops**

`while` loops let you repeat a block of code **as long as** a condition remains `True`. They’re handy when you don’t know ahead of time how many repetitions you’ll need.

---

## **1. Basic `while` Loop**

```python
counter = 1

while counter <= 5:
    print("Count:", counter)
    counter += 1
```

**Flow**  
1. Check `counter <= 5`.  
2. If `True`, run the body.  
3. Increment `counter`.  
4. Repeat until the condition becomes `False`.

---

## **2. `while` with Nested Conditionals**

Add `if` statements inside the loop for more control.

```python
number = 6

while number > 0:
    if number % 2 == 0:
        print(number, "is even")
    else:
        print(number, "is odd")
    number -= 1
```

---

## **3. Breaking Out Early with `break`**

```python
secret = "xyz"
attempts = 0

while attempts < 3:
    guess = input("Guess: ")
    if guess == secret:
        print("Correct!")
        break        # Exit loop immediately
    attempts += 1

if attempts == 3 and guess != secret:
    print("Out of tries.")
```

`break` stops the loop even if the condition is still `True`.

---

## **4. Skipping Ahead with `continue`**

```python
num = 0

while num < 10:
    num += 1
    if num % 2 == 0:
        continue    # Skip even numbers
    print(num)      # Prints only odd numbers
```

`continue` jumps back to the condition check, skipping the rest of the body.

---

## **Quick Reference**

| Keyword    | What It Does                                  |
|------------|-----------------------------------------------|
| `while`    | Repeat while a condition is `True`.           |
| `break`    | Exit the loop immediately.                    |
| `continue` | Skip to the next iteration.                   |
| Nested `if`| Add extra decision‑making inside the loop.    |

Master these patterns, and you’ll handle most looping tasks in Python with confidence.
