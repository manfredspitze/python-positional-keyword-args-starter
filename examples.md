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
### Tips for Working with Positional Arguments
- Remember that the number of arguments must match the number of parameters in your function
- The order of your positional arguments matters!
  - In the example above, the arguments 'Alyssa' and `30` match the order of the `first_name` and `age` parameters used with the `greet_user()` function
