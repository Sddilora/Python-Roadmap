# Python Syntax

## Comments

Single-line comments start with a hash symbol (#).
```python
# This is a single-line comment
```
Multi-line comments are enclosed between triple quotes (''' or """).

```python
'''
This is a multi-line comment.
It can span across multiple lines.
'''
```

## Variables and Data Types
Python has dynamic typing, so variables do not need to be explicitly declared. They are created when a value is assigned to them.
```python
name = "Dilara"  # String
age = 21  # Integer
height = 1.65  # Float
is_student = True  # Boolean
```

## Control flow
### Conditional Statements

```python
if condition:
    # code to execute when the condition is True
elif condition2:
    # code to execute when condition2 is True
else:
    # code to execute when all conditions are False
```

### Loops
```python
# For Loop:
for item in iterable:
    # code to execute for each item in the iterable

# While Loop
while condition:
    # code to execute while the condition is True
```

## Functions
```python
def function_name(arguments):
    # code inside the function
    return value  # optional
```

## Input and Output

### Printing Output
```python
print("Hello, python!")
```

### User Input
```python
name = input("Enter your name: ")
```

## Data Structures
### Lists
```python
my_list = [1, 2, 3, "apple", True]
```
### Dictionaries
```python
my_dict = {
    "name": "Dilara",
    "age": 21,
    "is_student": False
}
```
### Tuples
```python
my_tuple = (1, 2, "apple")
```

## Exception Handling

```python
try:
    # code that might raise an exception
except ExceptionType:
    # code to handle the exception
finally:
    # code to execute regardless of an exception

```