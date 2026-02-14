# Contributing to Spot Good Boi

Thank you for your interest in contributing! We welcome contributions from everyone.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps which reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include screenshots if possible**
- **Include robot environment details** (robot IP, SDK version, Python version, OS)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and the expected behavior**
- **Explain why this enhancement would be useful**

### Pull Requests

- Fill in the required template
- Follow the Python style guide (PEP 8)
- End all files with a newline
- Document new functionality
- Add comments for complex logic
- Avoid introducing dependencies unless absolutely necessary

## Development Setup

1. Fork the repo and clone it locally
2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Make your changes
5. Test thoroughly with a Spot robot or simulator
6. Commit with clear, descriptive messages
7. Push to your fork and submit a pull request

## Style Guidelines

### Python Code

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use meaningful variable and function names
- Keep lines under 100 characters where possible
- Add docstrings to functions and classes
- Use type hints where applicable

Example:
```python
def your_function(param1: str, param2: int) -> bool:
    """
    Brief description of what the function does.
    
    Args:
        param1: Description of param1
        param2: Description of param2
        
    Returns:
        Description of return value
    """
    pass
```

### Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Example:
```
Add emergency stop GUI feature

This adds a PyQt5-based GUI for emergency stopping the robot.
Fixes #123
```

### Documentation

- Update README.md if there are any user-facing changes
- Add comments explaining the "why" not the "what"
- Update CHANGELOG.md with significant changes

## Testing

Before submitting a pull request:

1. Test with actual Spot hardware or simulator if possible
2. Verify E-Stop functionality works correctly
3. Test all command paths
4. Check for memory leaks or resource issues

## Questions?

Feel free to open an issue with the "question" label if you have any questions about the codebase.

## Recognition

Contributors will be recognized in the project's acknowledgments section and in release notes for significant contributions.

Thank you for contributing to Spot Good Boi! 🐕
