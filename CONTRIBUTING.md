# Contributing Guidelines

Thank you for your interest in contributing to this repository. Please follow these guidelines to ensure consistency and quality.

## Code Style

### Python

- Follow PEP 8 style guide
- Use type hints when possible
- Write docstrings for functions and classes
- Use 4 spaces for indentation

Example:
```python
def process_data(data: list) -> dict:
    """
    Process the input data and return results.
    
    Args:
        data: List of data items to process
        
    Returns:
        Dictionary containing processed results
    """
    # Implementation here
    return {}
```

### JavaScript/Node.js

- Use ES6+ syntax
- Use semicolons
- Use 2 spaces for indentation
- Use camelCase for variables and functions
- Use PascalCase for classes

Example:
```javascript
/**
 * Fetch user data from API
 * @param {string} userId - The user ID
 * @returns {Promise<Object>} User data
 */
async function fetchUserData(userId) {
  // Implementation here
}
```

## Commit Messages

Follow the Conventional Commits specification:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that don't affect code meaning (formatting, missing semicolons)
- `refactor`: Code change that neither fixes a bug nor adds a feature
- `perf`: Code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to build process, dependencies, or tools

### Examples

```
feat(spotify-api): add playlist creation functionality

fix(databricks): resolve connection timeout issue

docs: update README with new installation steps

refactor: simplify data processing pipeline
```

## Pull Request Process

1. Create a feature branch from `main`
2. Keep commits clean and atomic
3. Update documentation as needed
4. Add tests for new functionality
5. Ensure all tests pass
6. Write a clear pull request description

## Testing

- Write tests for new features
- Ensure existing tests continue to pass
- Aim for >80% code coverage for new code

Run tests with:
```bash
# Python
python -m pytest tests/

# JavaScript
npm test
```

## Documentation

- Update README.md for major changes
- Add inline comments for complex logic
- Keep documentation in English
- Use clear, concise language

## Naming Conventions

### Branches

Use this format: `<type>/<short-description>`

Examples:
- `feature/spotify-playlist-sync`
- `fix/azure-authentication-bug`
- `docs/update-installation-guide`
- `refactor/data-pipeline`

### Files and Folders

- Use lowercase with hyphens for directories: `spotify-codex/`
- Use snake_case for Python files: `process_data.py`
- Use kebab-case for JavaScript files: `fetch-user-data.js`

## Questions or Suggestions?

Open an issue or contact the repository maintainer.

---

**Thank you for contributing!** 🎉
