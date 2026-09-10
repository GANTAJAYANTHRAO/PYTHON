# 🐍 Python Learning — Day 2

**Playlist:** CodeWithHarry Python Playlist  
**Progress:** Day 2 completed

---

## 1. Variables

### What is a Variable?

A variable is something like a **container** that holds data.

Creating a variable is like creating a **placeholder in memory** and assigning it a value.

```python
a = 1
```

Here:
- `a` is the variable.
- `1` is the value assigned to it.

### Why are Variables Important?

Variables allow us to:
- Store data
- Reuse stored data
- Perform calculations
- Store large values or sentences and refer to them using a variable name

---

# 2. Strings

A string represents text data.

When representing string data, we use quotes.

```python
b = "rao"
print(b)
```

Output:

```text
rao
```

---

# 3. Data Types

A **data type specifies the type of value a variable holds**.

Different types of data require different types of operations.

### Checking the Data Type

We can use the `type()` function:

```python
a = 1
print("The type of a is", type(a))
```

Output:

```text
The type of a is <class 'int'>
```

---

# 4. Complex Numbers

Complex numbers were introduced as another data type.

In Python, `j` is used for the imaginary part.

```python
a = 1 + 2j
print(a)
```

Output:

```text
(1+2j)
```

---

# 5. Boolean

Boolean values are used when responding to a condition.

A Boolean represents:

- `True`
- `False`

```python
a = True
print(a)
```

Output:

```text
True
```

---

# 6. Sequence Data

Sequence/collection data types covered in Day 2 include:

- List
- Tuple

## 6.1 List

A list is a **collection of different data elements**.

```python
a = [1, 2, 3, "Python"]
print(a)
```

A list can contain different types of values.

## 6.2 Tuple

A tuple is also a **collection of different data elements**.

The important difference covered in Day 2 is that the collection **cannot be changed** after it is created.

```python
a = (1, 2, 3, "Python")
print(a)
```

### Remember

> **List → Collection that can be changed**  
> **Tuple → Collection that cannot be changed**

---

# 7. Dictionary

A dictionary is a collection of **key-value pairs**.

It is mapped data where a key is associated with a value.

```python
student = {
    "name": "Rao",
    "age": 25
}
```

Here:
- `"name"` → key
- `"Rao"` → value
- `"age"` → key
- `25` → value

### Remember

> **Dictionary → Key-Value pairs**

---

# 8. Everything in Python is an Object

An important concept introduced in Day 2 is:

> **In Python, everything is an object.**

The detailed explanation of objects will be covered in upcoming classes.

---

# 9. Operators

Operators are used in Python to perform different types of operations.

## 9.1 Addition `+`

```python
print(11 + 2)
```

Output:

```text
13
```

## 9.2 Subtraction `-`

```python
print(11 - 2)
```

Output:

```text
9
```

## 9.3 Multiplication `*`

```python
print(11 * 2)
```

Output:

```text
22
```

## 9.4 Division `/`

```python
print(11 / 2)
```

Output:

```text
5.5
```

## 9.5 Floor Division `//`

Floor division gives the floor value of the division result.

```python
print(11 // 2)
```

Output:

```text
5
```

### Remember

> `//` → Floor Division

## 9.6 Modulus `%`

The modulus operator gives the **remainder** after division.

```python
print(11 % 2)
```

Output:

```text
1
```

### Remember

> `%` → Remainder

---

# 10. Basic Calculator Exercise

A basic calculator was created using:

- `input()`
- `int()`
- `if`
- `elif`
- `else`
- `or`
- `==`
- Variables
- Operators

### Code

```python
a = int(input("A : "))
operation = input("Enter the operator : ")

if operation == "+" or operation == "-" or operation == "*":
    b = int(input("B : "))

    if operation == "+":
        print(a + b)

    elif operation == "-":
        print(a - b)

    elif operation == "*":
        print(a * b)

else:
    print("Invalid operator")
```

## How the Calculator Works

### Step 1 — Take the first number

```python
a = int(input("A : "))
```

`input()` takes input from the user.

`int()` converts the entered value into an integer.

The result is stored in variable `a`.

### Step 2 — Take the operator

```python
operation = input("Enter the operator : ")
```

The entered operator is stored in `operation`.

### Step 3 — Validate the operator

```python
if operation == "+" or operation == "-" or operation == "*":
```

This checks whether the entered operator is supported.

`or` means that **at least one condition must be true**.

### Step 4 — Take the second number

```python
b = int(input("B : "))
```

The second number is taken only when a valid operator is entered.

### Step 5 — Perform the operation

```python
if operation == "+":
    print(a + b)

elif operation == "-":
    print(a - b)

elif operation == "*":
    print(a * b)
```

### Step 6 — Handle an invalid operator

```python
else:
    print("Invalid operator")
```

---

# 🔁 Quick Revision

### Variable
> A variable is like a container/placeholder used to hold data.

### String
> Text data represented using quotes.

### Data Type
> Specifies the type of value a variable holds.

### `type()`
> Used to find the data type of a value/variable.

### Complex Number
> Python represents complex numbers using `j` for the imaginary part.

### Boolean
> Represents `True` or `False`.

### List
> A collection of data elements that can be changed.

### Tuple
> A collection of data elements that cannot be changed.

### Dictionary
> A collection of key-value pairs.

### Object
> Everything in Python is an object. Detailed explanation comes later.

### Operators

| Operator | Operation |
|---|---|
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `//` | Floor division |
| `%` | Modulus / remainder |

---

---

**Next:** Day 3 🚀
