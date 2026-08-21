# Basic Syntax

```python
for item in iterable:
    print(item)
```

`for`{.python} is the keyword that starts the loop. `item`{.python} is the loop variable that takes on each value in turn from the iterable. The loop variable and iterable do not need to be named `item`{.python} and `iterable`{.python}; they can be variables with any name. The keyword `in`{.python} separates them. The colon starts the loop block, and indentation defines which lines run in each iteration.

In Python you can loop over any iterable type, including lists and strings.

# List Example

In this example, we loop over a list of numbers, printing the value of each item in the list:

```py-cell
my_list = [1, 2, 4, 5]
for item in my_list:
    print("Start of iteration")
    print(item)
print("All done")
```

# String Example

In this example, we loop over a string, printing each character:

```py-cell
my_string = "Hello"
for char in my_string:
    print(char)
```

# Execution Order

1. Take the next value from the iterable.
2. Assign it to the loop variable.
3. Run all indented lines.
4. Move to the next value, or finish if none remain.

