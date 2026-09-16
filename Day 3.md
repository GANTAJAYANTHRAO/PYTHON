🐍 Python Learning — Day 3

Playlist: CodeWithHarry Python Playlist
Topic: Type Casting, User Input, Strings, String Indexing, Slicing & String Methods

1. Type Casting / Type Conversion

What is Type Casting?

The conversion of one data type into another data type is known as type casting or type conversion in Python.

For example:

a = "27"

The value 27 is inside double quotes, so it is a string.

To convert it into an integer:

a = int("27")

1.1 Type Conversion Functions

Functions covered:

int()
float()
tuple()
set()
list()
dict()

These are conversion functions used to convert values into other data types.

1.2 Example

a = "1"
b = "2"

print(int(a) + int(b))

Output:

3

The strings are converted to integers before performing addition.

1.3 Valid Values Are Required

The value being converted must be valid for the target type.

For example:

a = "27"
print(int(a))

This is valid because "27" represents an integer.

2. Types of Type Casting

There are two types:

Explicit Type Casting

Implicit Type Casting

2.1 Explicit Type Casting

Explicit type casting is when the developer manually converts one data type into another according to the requirement.

Example:

a = "10"
a = int(a)

print(a)

Explicit → Developer manually performs the conversion.

2.2 Implicit Type Casting

Implicit type casting occurs when Python performs a conversion automatically during a compatible operation involving different data types.

Example:

a = 10
b = 2.5

print(a + b)

Output:

12.5

Implicit → Python performs the conversion automatically.

3. Taking User Input in Python

Python allows us to take user input directly using the input() function.

Example:

name = input("Enter your name: ")

The value entered by the user is returned by input() and can be stored in a variable.

Important

The value returned by input() is a string.

For numerical operations, we can convert the input:

age = int(input("Enter your age: "))

Here:

input() takes the user's input.

The input is initially a string.

int() converts it into an integer.

The result is stored in age.

4. Strings

Anything enclosed between single quotes or double quotes is considered a string.

Examples:

name = "Jayanth"

or:

name = 'Jayanth'

Both represent string values.

5. Multi-Line Strings

If we want to write a string across multiple lines, we can use triple quotes.

Example:

rao = """Hey
hii i am
from
rao cricket
academy"""

print(rao)

Output:

Hey
hii i am
from
rao cricket
academy

6. Strings as a Sequence of Characters

In Python, a string can be accessed as a sequence of characters.

Example:

name = "jayanth"
print(name[3])

Output:

a

The character is accessed using its index.

7. String Indexing

Python uses zero-based indexing.

For:

name = "jayanth"

the positions are:

j → 0
a → 1
y → 2
a → 3
n → 4
t → 5
h → 6

Therefore:

print(name[3])

produces:

a

8. String Slicing

Slicing is used to extract a portion of a string.

The general syntax is:

string[start:end]

The start index is included and the end index is not included.

Example:

name = "Ganta Jayanth Rao, Hari Kaushal"

print(name[0:10])

This extracts the characters from index 0 up to, but not including, index 10.

8.1 Slicing from Index 1 to 4

print(name[1:4])

Indexes 1, 2, and 3 are included. Index 4 is not included.

9. Omitting the Start Index

We can omit the start index:

print(name[:4])

Python considers the starting point to be 0.

So:

name[:4]

means:

name[0:4]

10. String Length — len()

The len() function is used to find the length of a string.

Example:

name = "Ganta Jayanth Rao, Hari Kaushal"

print(len(name))

Output:

31

11. () vs []

Parentheses ()

Used when calling functions.

len(name)

Square Brackets []

Used for indexing and slicing.

name[3]
name[1:4]

Remember

() → Function call
[] → Indexing / Slicing

12. Negative Indexing

Python also supports negative indexes.

Negative indexes count from the end of the string.

For:

fruit = "mango"

the positions can be viewed as:

m → 0 / -5
a → 1 / -4
n → 2 / -3
g → 3 / -2
o → 4 / -1

Example:

print(fruit[-3:-1])

This selects the characters at -3 and -2.

Output:

ng

12.1 Understanding Negative Indexes

For:

fruit = "mango"

the length is 5.

So:

len(fruit) - 3 = 2
len(fruit) - 1 = 4

Therefore:

fruit[-3:-1]

corresponds to:

fruit[2:4]

which gives:

ng

13. String Methods

String methods are functions associated with strings that allow us to perform operations on them.

13.1 rstrip()

rstrip() removes trailing characters from the right side of a string.

Example:

rao = "jayath#"

print(rao.rstrip("#"))

Output:

jayath

14. replace()

The replace() method replaces one value with another inside a string.

Example:

rao = "jayath#"

print(rao.replace("#", "*"))

Output:

jayath*

15. capitalize()

capitalize() changes the first character of the string to uppercase and converts the remaining characters to lowercase.

Example:

rao = "jayanth"

print(rao.capitalize())

Output:

Jayanth

16. count()

The count() method returns the number of times a given value occurs within a string.

Example:

rao = "jayanth"

print(rao.count("a"))

This returns the number of times "a" occurs in the string.

17. endswith()

endswith() checks whether a string ends with a specified value.

It returns:

True if the string ends with the given value

False otherwise

Example:

rao = "jayanth!!!!"

print(rao.endswith("!!!!"))

Output:

True

🔁 Quick Revision

Type Casting

Converting one data type into another data type.

Explicit Type Casting

Conversion manually performed by the developer.

Implicit Type Casting

Conversion performed automatically by Python during compatible operations.

input()

Used to take input from the user. The returned input is a string.

String

Text enclosed in single or double quotes.

Triple Quotes

Used to create multi-line strings.

Indexing

Accessing individual characters using their position.

Zero-Based Indexing

The first character has index 0.

Slicing

Extracting part of a string using start:end.

len()

Returns the length of a string.

Negative Indexing

Counts characters from the end of the string.

rstrip()

Removes trailing characters from the right side.

replace()

Replaces one value with another in a string.

capitalize()

Capitalizes the first character and lowercases the remaining characters.

count()

Counts occurrences of a value in a string.

endswith()

Checks whether a string ends with a specified value.
