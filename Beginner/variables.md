# Variables
## Variables are containers for storing data values.
## Unlike other programming languages, Python has no command for declaring a variable.
## A variable is created the moment you first assign a value to it.
## Variables do not need to be declared with any particular type and can even change type after they have been set.
## Variable Names
### A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume).
### Rules for Python variables:
- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
## Assign Value to Multiple Variables
### Python allows you to assign values to multiple variables in one line:
 ```python
x, y, z = "Orange", "Banana", "Cherry"
```
### And you can assign the same value to multiple variables in one line:
```python
x = y = z = "Orange"
```
### String variables can be declared either by using single or double quotes:
```python
x = "John"
# is the same as
x = 'John'
```

## Output Variables
### The Python print statement is often used to output variables.
### To combine both text and a variable, Python uses the + character:
```python
x = "awesome"
print("Python is " + x)
# Output: Python is awesome
```
## Casting
### Specify a Variable Type
### There may be times when you want to specify a type on to a variable. This can be done with casting. Python is an object-orientated language, and as such it uses classes to define data types, including its primitive types.
### Casting in python is therefore done using constructor functions:
```python
x = str(3) # str
y = int(3) # int
z = float(3) # float
```
## Get the Type
### You can get the data type of a variable with the type() function.
```python
x = 5
print(type(x))
# Output: <class 'int'>
```

