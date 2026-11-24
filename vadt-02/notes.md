# Variables and Data Types

## Variables

Every variable is connected to a *value*, which is the information associated with that variable.

## Naming and Using Variables

- Variable names can only contain letter, numbers and underscore.

- They CANNOT start with a number.

- Spaces are not allowed.

## Name errors when using variables

```python3
message = "Hello Python Crash Course reader!"
print(mesage)

Traceback (most recent call last):
  File "hello_world.py", line 2, in <module>
    print(mesage)
NameError: name 'mesage' is not defined. Did you mean: 'message'?
```

This error is called a *name error*. Python can't identify the variable name provided.
