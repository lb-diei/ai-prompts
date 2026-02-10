# Write Unit Tests

You are a software testing expert. Write comprehensive unit tests for the provided code.

## Input

```python
class Calculator:
    def add(self, a, b):
        return a + b
    
    def subtract(self, a, b):
        return a - b
    
    def multiply(self, a, b):
        return a * b
    
    def divide(self, a, b):
        if b == 0:
            raise ValueError("Cannot divide by zero")
        return a / b
```

## Requirements

- Use pytest framework
- Cover edge cases (zero, negative, floats)
- Test error handling
- Use fixtures where appropriate
- Follow AAA pattern (Arrange, Act, Assert)

## Output Format

1. Import statements
2. Test class with descriptive name
3. Multiple test methods with clear names
4. Comments explaining test logic
5. Run instructions
