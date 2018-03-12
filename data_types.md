# Data Types

## Boolean
Booleans are either **True** or **False**
```python
is_true = True
```
## Integers
Integers are numbers without floating point (decimal) precision. They can be set like this example:
```python
number = 11
```
Integer math is nativly supported.
```python
num1 = 5
num2 = 5
print(num1+num2)
>> 10
```
## Floats
Floats are numbers with decimal precision.
```python
number = 1.1
```
## Strings
Strings are strings of characters.
```python
name = "Michael Hunt"
```
## Lists
Lists are lists of other data types. Python is cool in the sense that you can place arbitrary data types within a list. Lists have methods that allow for appending and removing in addition to other functions.
```python
my_list = ["Apple", "Plum", "Orange"]
my_list.append("Banana")
print(my_list)
>> ['Apple', 'Plum', 'Orange', 'Banana']
my_list.remove("Apple")
print(my_list)
>> ['Plum', 'Orange', 'Banana']
```
> Exercise: Create a list of names and append the name "Nicky" to it.

## Sets
Sets are a data type that supports unique items. They are similar to lists save for the fact that all elements must be unique.
```python
a_set = set(["Apple", "Plum", "Orange"])
```
## Tuples
Tuples are immutable (Unable to be changed) lists. They are usually preferred when dealing with large amounts of data as they do not have the memory overhead of a list.
```python
my_tuple = ("Apple", "Plum", "Orange")
```
## Dictionaries
Dictionaries are maps of keys to values. They allow you to lookup the value in a table by its key/name.
```python
phonebook = {"Mike": "999-999-9999", "Jay": "888-888-8888"}
print(phonebook["Mike"])
>> "999-999-9999"
```
