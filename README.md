# Python-learning-Day2

1. Logical Operators
Logical operators are used to combine conditional statements:
and=	Returns True if both conditions are true	(5 > 3) and (4 < 6) -> True
or=	Returns True if at least one condition is true	(5 < 3) or (4 < 6) -> True
not=	Reverses the result (negation)	not(5 > 3) -> False
code(syntax):-
x = 10
y = 5

# Logical AND
print(x > 5 and y < 10)  # True

# Logical OR
print(x < 5 or y < 10)   # True

# Logical NOT
print(not(x == 10))      # False

2. Membership Operators
Membership operators test for membership in sequences like lists, tuples, strings, etc.
in=	Returns True if a value exists in the sequence	'a' in 'apple' -> True
not in=	Returns True if a value does NOT exist in the sequence	3 not in [1, 2, 4] -> True
code(syntax):-
fruits = ["apple", "banana", "cherry"]

# Membership Test
print("banana" in fruits)      # True
print("grape" not in fruits)   # True

3. Identity Operators
Identity operators compare the memory location of two objects (whether they are the same object in memory).
is=	Returns True if both variables point to the same object	a is b
is not=	Returns True if both variables point to different objects	a is not b
code(syntax):-
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)       # True (same object)
print(a is c)       # False (different objects with same content)
print(a is not c)   # True


Here's a breakdown of logical operators, membership operators, identity operators, and conditional statements (if, else, elif) in Python:

1. Logical Operators
Logical operators are used to combine conditional statements:

Operator	Description	Example
and	Returns True if both conditions are true	(5 > 3) and (4 < 6) → True
or	Returns True if at least one condition is true	(5 < 3) or (4 < 6) → True
not	Reverses the result (negation)	not(5 > 3) → False
Example:

python
Copy
Edit
x = 10
y = 5

# Logical AND
print(x > 5 and y < 10)  # True

# Logical OR
print(x < 5 or y < 10)   # True

# Logical NOT
print(not(x == 10))      # False
2. Membership Operators
Membership operators test for membership in sequences like lists, tuples, strings, etc.

Operator	Description	Example
in	Returns True if a value exists in the sequence	'a' in 'apple' → True
not in	Returns True if a value does NOT exist in the sequence	3 not in [1, 2, 4] → True
Example:

python
Copy
Edit
fruits = ["apple", "banana", "cherry"]

# Membership Test
print("banana" in fruits)      # True
print("grape" not in fruits)   # True
3. Identity Operators
Identity operators compare the memory location of two objects (whether they are the same object in memory).

Operator	Description	Example
is	Returns True if both variables point to the same object	a is b
is not	Returns True if both variables point to different objects	a is not b
Example:

python
Copy
Edit
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)       # True (same object)
print(a is c)       # False (different objects with same content)
print(a is not c)   # True

4. Conditional Statements (if, elif, else)
Conditional statements allow you to execute code based on specific conditions.
Syntax:-
if condition:
    # Code block (executes if condition is True)
elif another_condition:
    # Executes if 'if' was False, but this is True
else:
    # Executes if all previous conditions were False

code:-
age = 18

if age < 18:
    print("You are a minor.")
elif age == 18:
    print("You just became an adult!")
else:
    print("You are an adult.")


