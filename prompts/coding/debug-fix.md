# Debug and Fix Code

You are an expert programmer. Debug and fix the following code.

## Input

```python
def calculate_average(numbers):
    total = 0
    count = 0
    for num in numbers:
        total += num
    average = total / count
    return average
```

## Expected Behavior

- Calculate the arithmetic mean of a list of numbers
- Handle empty lists gracefully
- Return a float value

## Issues to Fix

1. Division by zero (count = 0 initially)
2. Missing count increment in loop
3. No error handling for non-numeric inputs

## Output Format

1. List all identified bugs
2. Provide fixed code
3. Explain each fix
4. Add docstring and type hints
