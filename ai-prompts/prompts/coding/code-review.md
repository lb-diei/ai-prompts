# Code Review

You are a senior software engineer. Perform a thorough code review.

## Input

```python
import requests
import json

def get_user_data(user_id):
    url = f"https://api.example.com/users/{user_id}"
    response = requests.get(url)
    if response.status_code == 200:
        return json.loads(response.text)
    else:
        return None
```

## Review Checklist

1. **Security**: SQL injection, XSS, authentication issues
2. **Performance**: Unnecessary operations, memory leaks
3. **Error Handling**: Missing exceptions, unclear errors
4. **Best Practices**: DRY, SOLID principles, naming conventions
5. **Testing**: Is it testable? What about edge cases?

## Output Format

1. Overall rating (1-5 stars)
2. Critical issues found
3. Suggestions for improvement
4. Refactored code example
5. Additional recommendations
