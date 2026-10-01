🐍 Python Learning — Day 4

Playlist: CodeWithHarry Python Playlist
Topic: if, if-else, elif, Conditions & Basic Conditional Exercises

1. Conditional Statements

Sometimes a programmer needs to check the evaluation of a certain expression to determine whether it evaluates to True or False.

If the expression evaluates to False, the program can follow a different execution path than it would have followed if the expression evaluated to True.

This is the basic idea behind conditional statements.

2. if Statement

An if statement is used to check a condition.

If the condition evaluates to True, the code inside the if block is executed.

Example

a = int(input("Enter the age:"))
print("Your age is:", a)

if(a > 18):
    print("Your eligible to drive")
else:
    print("Your not eligible to drive")

How it works

First, the program takes the user's age:

a = int(input("Enter the age:"))

Then it checks:

a > 18

If the condition is True, the program executes:

print("Your eligible to drive")

If the condition is False, the program executes the else block:

print("Your not eligible to drive")

3. if-else Statement

The if-else structure allows the program to choose between two different execution paths.

Structure

if condition:
    # code when condition is True
else:
    # code when condition is False

Example

age = 20

if age > 18:
    print("Your eligible to drive")
else:
    print("Your not eligible to drive")

4. Conditions and Boolean Results

A condition is an expression that can be evaluated as either:

True

or:

False

For example:

age > 18

If age is 20:

20 > 18 → True

If age is 16:

16 > 18 → False

The result determines which part of the program gets executed.

5. User Input with Conditions

We can combine input() with conditions.

Example:

a = int(input("Enter the age:"))

Here:

input() takes the value from the user.

The entered value is initially received as a string.

int() converts it to an integer.

The integer is stored in variable a.

The value can then be used in a condition:

if(a > 18):
    ...

6. Fruit Budget Exercise

A budget-based fruit exercise was created using:

input()

int()

Dictionary

sum()

values()

if

elif

else

Arithmetic operations

Code

import math

budget = 450
apple = int(input("Enter the apple cost:"))
pineapple = int(input("Enter the pineapple cost:"))
orange = int(input("Enter the orange cost:"))

fruits = {"apple": apple, "pineapple": pineapple, "orange": orange}
balance = budget - sum(fruits.values())

if(budget - apple >= 70):
    print("Add to cart")
elif(budget - balance >= 50):
    print("Add to cart")
elif(budget - balance >= 30):
    print("Add to cart")
elif(budget - balance >= 10):
    print("Add to cart")
else:
    print("Not of limit")

total_cost = sum(fruits.values())
print("Total Cost of the fruits : ", total_cost)

Amount_left = budget - total_cost
print("Balance Amount : ", Amount_left)

7. Understanding the Fruit Dictionary

The fruit prices are stored in a dictionary:

fruits = {
    "apple": apple,
    "pineapple": pineapple,
    "orange": orange
}

The dictionary contains:

Key         Value
-------------------------
apple       Apple cost
pineapple   Pineapple cost
orange      Orange cost

8. sum(fruits.values())

The expression:

fruits.values()

gets the values stored in the dictionary.

For example:

fruits = {
    "apple": 50,
    "pineapple": 100,
    "orange": 40
}

Then:

sum(fruits.values())

calculates:

50 + 100 + 40 = 190

9. Calculating the Balance

The initial balance is calculated using:

balance = budget - sum(fruits.values())

For example:

Budget = 450
Total fruit cost = 190

Balance = 450 - 190
        = 260

10. if / elif / else

The fruit exercise uses multiple conditions:

if(budget - apple >= 70):
    print("Add to cart")
elif(budget - balance >= 50):
    print("Add to cart")
elif(budget - balance >= 30):
    print("Add to cart")
elif(budget - balance >= 10):
    print("Add to cart")
else:
    print("Not of limit")

The conditions are checked in order.

The program enters the first matching branch.

If the if condition is not satisfied, Python checks the first elif.

If that is also false, Python checks the next elif.

If none of the conditions are satisfied, the else block is executed.

11. Calculating Total Cost

The total cost of all fruits is:

total_cost = sum(fruits.values())

Then it is displayed:

print("Total Cost of the fruits : ", total_cost)

12. Calculating Remaining Amount

The remaining amount is calculated using:

Amount_left = budget - total_cost

Then it is displayed:

print("Balance Amount : ", Amount_left)

🔁 Quick Revision

Conditional Statement

A conditional statement allows the program to choose different execution paths based on whether a condition evaluates to True or False.

if

Executes a block when its condition is True.

else

Executes a block when the if condition is False.

elif

Allows additional conditions to be checked when earlier conditions are False.

Condition

An expression that evaluates to True or False.

input()

Takes input from the user.

int()

Converts a value into an integer when the value is valid for integer conversion.

Dictionary

Stores data as key-value pairs.

values()

Gets the values from a dictionary.

sum()

Calculates the total of numeric values.
