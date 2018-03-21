# Functions
Functions are blocks of code that are called and return a value. They are formatted with **def** (Short for define) followed by a name and parameters. Parameters are what a function "takes in" before returning a value.

## Formatting
Let's look at a function that takes a number and returns its square.
```python
def square(num1):
  result = num1**2
  return result
```
Python uses tabs to define what's inside of a function. If you do not indent, Python will not recognize the lines as part of the function.

## Calling a function
Functions are called by stating the name of the function, followed by its parameters inside of parenthesis.
```python
square(2)
>> 4
```

## Positional vs. Named
Sometimes when a function takes more than one parameter, things can get confusing. When you call a function with more than one parameter, Python will assume that you are setting them as defined in the order of the function.
```python
def say_hello(greeting, name):
  print(greeting + ' ' + name)
say_hello("Hello", "Chuck")
>> "Hello Chuck"
```
When a function takes multiple parameters, it can be tricky to remember the order they were defined in the function. In this case, you can use named parameters instead.
```python
def say_hello(greeting, name):
  print(greeting + ' ' + name)
say_hello(name="Chuck", greeting="Hello")
>> "Hello Chuck"
```

## Exercise Question 1
```python
new_items = ['Apple', 'Orange', 'Pear', 'Grapes']
inventory = {'Apple': 5, 'Pear': 3, 'Grapes': 6}

def add_to_inventory(new_items, inventory):
    # For each item in the new_items list,
    # increment the inventory dictionary by 1
    # If the item doesn't exist, add it to the inventory
    return inventory
```
