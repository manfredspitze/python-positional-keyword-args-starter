## Python Functions: Positional & Keyword Arguments

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
  - In the example above, the arguments `'Alyssa'` and `30` match the order of the `first_name` and `age` parameters used with the `greet_user()` function
 

### Keyword Arguments

- With positional arguments, it is sometimes hard to tell which argument to use with which parameter
- Keyword arguments can make your code easier to read and understand:
```python
# Calling a function to calculate the area of a rectangle
calculate_area_rectangle (width = 10, height = 5) # This code is easier to read

# Calling a function to calculate the area of a rectangle
calculate_area_rectange (10, 5) # Harder to see which number is the width and which is the height of the rectangle
```
- With **keyword arguments**, the exact order of your arguments (when you call a function) is less important than when you use positional arguments
```python
# Calling a function to calculate the area of a rectangle
calculate_area_rectangle (width = 10, height = 5) # Note the order of the two arguments in this version

# Calling a function to calculate the area of a rectangle
calculate_area_rectangle (height = 5, width = 10) # Changing the order of keyword arguments does not affect the result of the calculation
```
