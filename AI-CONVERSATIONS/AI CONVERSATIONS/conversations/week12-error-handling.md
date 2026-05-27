# Week 12 — Error Handling & Validation

## Objective
Create tests for system resilience and error handling.

## User Prompt
"Create tests that verify error handling for:
- Invalid file uploads
- Network connection issues
- Malformed data
- User input validation
Ensure error messages are user-friendly and helpful."

## Work Completed
- Tested invalid file uploads
- Simulated network failures
- Validated malformed data handling
- Implemented user input validation

## Key Learnings
- Error handling is as important as core functionality
- Helpful messages improve user experience
- Defensive programming reduces application crashes

## Example Validation
```python
if len(question.strip()) == 0:
    return {
        "valid": False,
        "error": "Please enter a question."
    }
```

## Reflection
This phase improved the robustness and professionalism of the application.