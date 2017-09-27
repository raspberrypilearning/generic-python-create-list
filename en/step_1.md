A Python list is a type of data structure. It can hold collections of any data type, and even a mixture of data types. Here is an empty list:

```python
an_empty_list = []
```

You can create a list by giving it a name and adding the items of data inside square brackets:

```python
compass = ["north", "south", "east", "west"]
```

Once a list has been created, you can add more data to the list using `append`:

```python
numbers = [5, 10, 15, 20]
numbers.append(25)
print(numbers)

[5, 10, 15, 20, 25]
```

You can get rid of a piece of data from the list using `remove`:

```python
numbers.remove(5)
print(numbers)

[10, 15, 20, 25]
```
