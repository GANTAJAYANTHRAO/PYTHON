# 🐍 Python Learning — Day 1

**Playlist:** CodeWithHarry Python Playlist
**Progress:** 4 / 100 Videos Completed

---

## 1. Programming Basics

### What is Programming?

Programming is nothing but **telling the computer what to do**.

Computers cannot directly understand our requirements. To communicate instructions to a computer, we use **programming languages**.

**Example:** Python is a programming language.

### Simple Definition

> **Programming = Giving instructions to a computer to perform a required task.**

---

# 2. Python

Python is a:

* **Dynamically typed** programming language
* **High-level** programming language
* Language with strong **library support**

---

## 2.1 Dynamically Typed Language

Python is dynamically typed because we do not need to explicitly specify the data type of a variable when creating it.

Python determines the type of the value at **runtime**.

### Example

```python
x = 10
print(x)
```

Here, Python understands that `x` contains an integer value.

We can later assign a different type of value:

```python
x = "Hello"
print(x)
```

Now `x` contains a string.

### Remember

> In Python, we don't need to explicitly declare the variable's data type.

---

# 3. High-Level vs Low-Level Languages

## High-Level Language

A high-level language is easier for humans to understand because it uses relatively simple and readable syntax.

### Example

```python
print("Hello World")
```

The above code is easy for a human to understand.

---

## Low-Level Language

A low-level language is closer to the **hardware and machine instructions**.

It is commonly used when direct interaction with hardware is required.

### Examples of areas where low-level programming is useful

* Operating systems
* Embedded systems
* Hardware-level programming

### Quick Comparison

| High-Level Language             | Low-Level Language     |
| ------------------------------- | ---------------------- |
| Easier for humans to understand | Closer to hardware     |
| Simpler/readable syntax         | More machine-oriented  |
| Easier to write                 | More hardware-oriented |
| Example: Python                 | Example: Assembly      |

### Remember

> **High-level → Human-friendly**
> **Low-level → Machine/Hardware-friendly**

---

# 4. Modules

A **module** is a reusable piece of code that can be used in another Python program.

Modules allow us to **reuse code written by others** instead of writing everything from scratch.

### Simple Definition

> **Module = Reusable code that can be imported and used in our program.**

---

## 4.1 Types of Modules

There are two types of modules covered:

1. **Built-in / Standard Modules**
2. **External Modules**

---

## Built-in / Standard Modules

These modules are provided as part of Python's standard library.

They generally do not need to be installed separately.

### Example

```python
import math

print(math.sqrt(25))
```

Here, `math` is a standard Python module.

---

## External Modules

External modules/packages are created outside Python's standard library.

They generally need to be installed before they can be used.

### Example

**TensorFlow**

TensorFlow is an external Python library/package.

After installing it, it can be imported:

```python
import tensorflow
```

### Remember

> **Built-in / Standard → Provided with Python's standard library**
> **External → Comes from outside the standard library**

---

# 5. First Python Program

## `print()`

`print()` is a **built-in function** used to display information on the screen.

### Example

```python
print("Hello World")
```

### Output

```text
Hello World
```

### Important

`print()` is a **function**, not a module.

---

# 6. Comments

Comments are **text notes added to a program to provide explanatory information about the source code**.

Comments are mainly written for people reading and understanding the code.

### Example

```python
# This is a comment

print("Hello")
```

The comment explains the code but is not executed as a normal program instruction.

### Why use comments?

Comments can help us:

* Explain what code is doing
* Make code easier to understand
* Make code easier to maintain

---

# 7. Escape Sequences

Escape sequences are used to insert characters or special formatting that cannot be directly written in the usual way inside a string.

An escape sequence starts with a **backslash (`\`)** followed by a character.

---

## 7.1 `\n` — New Line

`\n` is used to move the text to a new line.

### Example

```python
print("Hello\nWorld")
```

### Output

```text
Hello
World
```

---

## 7.2 `\t` — Tab Space

`\t` inserts a tab space.

### Example

```python
print("Hello\tWorld")
```

### Output

```text
Hello    World
```

---

## 7.3 `\"` — Double Quote

Used when we want to include a double quote inside a string surrounded by double quotes.

### Example

```python
print("He said \"Hello\"")
```

### Output

```text
He said "Hello"
```

---

## 7.4 `\'` — Single Quote

Used when we want to include a single quote inside a string surrounded by single quotes.

### Example

```python
print('It\'s good')
```

### Output

```text
It's good
```

---

## 7.5 `\\` — Actual Backslash

Used when we want to print an actual backslash.

### Example

```python
print("C:\\Python\\main.py")
```

### Output

```text
C:\Python\main.py
```

---

## Escape Sequence Quick Reference

| Escape Sequence | Meaning          |
| --------------- | ---------------- |
| `\n`            | New line         |
| `\t`            | Tab space        |
| `\"`            | Double quote     |
| `\'`            | Single quote     |
| `\\`            | Actual backslash |

---

# 8. Separator — `sep`

`sep` is an optional parameter of the `print()` function.

It controls what is placed **between multiple values** passed to `print()`.

### Example

```python
print("GANTA", "JAYANTHRAO", 86880, 29201, sep=" ")
```

### Output

```text
GANTA JAYANTHRAO 86880 29201
```

We can also use another separator.

### Example

```python
print("GANTA", "JAYANTHRAO", 86880, 29201, sep="-")
```

### Output

```text
GANTA-JAYANTHRAO-86880-29201
```

### Remember

> **`sep` → controls what comes BETWEEN values.**

---

# 9. `end` Parameter

`end` is an optional parameter of the `print()` function.

It controls what is printed **at the end of the output**.

By default, `print()` ends with a new line.

### Example

```python
print("Loading", end="...")
print("Done!")
```

### Output

```text
Loading...Done!
```

Here:

```python
end="..."
```

means that instead of moving to a new line after `"Loading"`, Python prints `...`.

### Remember

> **`end` → controls what comes at the END of a `print()` call.**

---

# 10. `sep` vs `end`

| Parameter | Purpose                                                  |
| --------- | -------------------------------------------------------- |
| `sep`     | Controls what appears **between multiple values**        |
| `end`     | Controls what appears **at the end of the print output** |

### Example

```python
print("Hello", "World", sep="-")
```

Output:

```text
Hello-World
```

Here `sep` controls the `-` between the values.

---

```python
print("Hello", end="...")
```

Output:

```text
Hello...
```

Here `end` controls what is printed after `Hello`.

---

# 🔁 Quick Revision

### Programming

> Programming means giving instructions to a computer.

### Python

> Python is a dynamically typed, high-level programming language with strong library support.

### Dynamic Typing

> Python determines the data type at runtime, so explicit type declaration is generally not required.

### High-Level Language

> Easier for humans to read and write.

### Low-Level Language

> Closer to hardware and machine instructions.

### Module

> Reusable code that can be imported and used in another program.

### `print()`

> A built-in function used to display information on the screen.

### Comments

> Notes added to source code to explain the program.

### Escape Sequences

> Backslash-based sequences used to represent special characters or formatting inside strings.

### `sep`

> Controls what appears **between values**.

### `end`

> Controls what appears **at the end** of `print()`.

---

## 🧠 Things I Should Be Able to Explain

After completing Day 1, I should be able to explain:

* What programming is
* Why programming is required to communicate with computers
* What Python is
* What dynamically typed means
* Difference between high-level and low-level languages
* What a module is
* Difference between standard and external modules
* What `print()` does
* What comments are
* What escape sequences are
* `\n`, `\t`, `\"`, `\'`, and `\\`
* What `sep` does
* What `end` does
* Difference between `sep` and `end`

---

**Next:** Day 2 🚀
