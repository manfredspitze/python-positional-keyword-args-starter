## Python: Positional & Keyword Arguments

### Positional Arguments

- Positional is a fancy word for **position**
- Positional arguments are assigned to parameters based on their order in the function call
- In the example below, 'Alyssa' is assigned to the parameter `first_name` and 30 is assigned to the `age` parameter

```python
# Example
def greet_user(first_name, age):
print(f"Hello, {first_name}. You are {age} years old.")

greet_user("Alyssa", 30)
```

```python
# OUTPUT
Hello, Alyssa. You are 30 years old.
```
