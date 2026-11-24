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

You should think of variables in python as labels that you can assign to values.

## Changing Case in a String with Methods

```python3
name = "ada lovelave"
print(name.title())
```

The method `title()` appears after the variable in the `print()` call. A *method* is an action that Python can perform on a piece of data. The dot tells Python to make the title method act on the variable `name`. 

Every method is followed by a pair of parentheses.

## Using Variables in Strings

To combine 2 strings, you can use *f-strings* to format them: 

```python3
first_name = "ada"
last_name = "lovelace"
full_name = f"{first_name} {last_name}"
print(f"Hello, {full_name.title()}!")
```

## Adding Whitespace to Strings with Tabs or Newlines
