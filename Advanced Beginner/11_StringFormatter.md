In Python, string formatting allows you to create strings with placeholders that are replaced by values at runtime. There are several methods for string formatting, including using the `%` operator, the `str.format()` method, and f-strings (formatted string literals).

### Using `%` Operator:

```python
name = "Alice"
age = 30
formatted_string = "Hello, %s! You are %d years old." % (name, age)
print(formatted_string)
# Output: Hello, Alice! You are 30 years old.
```

### Using `str.format()` Method:

```python
name = "Bob"
age = 25
formatted_string = "Hello, {}! You are {} years old.".format(name, age)
print(formatted_string)
# Output: Hello, Bob! You are 25 years old.
```

### Using f-Strings (Formatted String Literals):

```python
name = "Charlie"
age = 35
formatted_string = f"Hello, {name}! You are {age} years old."
print(formatted_string)
# Output: Hello, Charlie! You are 35 years old.
```

### Formatting Specifiers:

You can specify formatting options within the placeholders to control how values are formatted.

- `%s`, `%d`, `%f`: String, Integer, Float.
- `%x`, `%o`: Hexadecimal, Octal.
- `{:}`: General placeholder in `str.format()` method.
- `{:<}`, `{:>}`, `{:^}`: Left-aligned, Right-aligned, Center-aligned.
- `{:.2f}`: Format floating-point number with 2 decimal places.

### Example:

```python
name = "David"
age = 40
height = 5.9
formatted_string = "Name: {:10}, Age: {:>5}, Height: {:.2f}".format(name, age, height)
print(formatted_string)
# Output: Name: David     , Age:    40, Height: 5.90
```

String formatting in Python provides a flexible way to create formatted strings with placeholders that can be replaced by values. It allows for cleaner and more readable code, especially when dealing with dynamic content.
