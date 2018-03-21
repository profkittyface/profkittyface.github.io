# Loops

## For Loops
For loops are ways of performing an action on multiple items in a list.
```python
names = ["Mayble", "Mike", "Ben"]
for name in names:
  print(name)
>> "Mayble"
>> "Mike"
>> "Ben"
```
After the **for** keyword, you define a name for the variable of a single item in a list. Python will then enter the for loop and perform what you define using the placeholder of the variable name you set (In this case **name**)

You may also notice that lines that are inside of the loop must be indented. Whenever an operation is part of a loop, it must be indented underneath the **for** keyword.

## While Loops
While loops will continue to loop as long as the condition is **True**
```python
counter = 0
while counter < 100:
  print(counter)
  counter = counter + 1
```
