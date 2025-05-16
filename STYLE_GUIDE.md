# Style Guide

This style guide outlines the coding standards and best practices for contributing to Petitionary. Following these guidelines helps maintain a clean, readable, and consistent codebase.

## General Principles

- **Readability over cleverness**: Write code that's easy to understand
- **Consistency**: Follow existing patterns in the codebase
- **Documentation**: Add comments for complex logic and document public APIs
- **Testability**: Write code that can be easily tested

## JavaScript/TypeScript Guidelines

### Formatting

- Use 2 spaces for indentation
- Use semicolons at the end of statements
- Line length should not exceed 100 characters
- Use single quotes for strings, except when avoiding escaping
- Add trailing commas in multi-line object/array literals
- Place opening braces on the same line as the statement

### Naming Conventions

- Use `camelCase` for variables, functions, and methods
- Use `PascalCase` for classes, interfaces, types, and React components
- Use `UPPER_CASE` for constants
- Use descriptive names that explain purpose (avoid abbreviations)

### React Specific

- One component per file
- Use functional components with hooks instead of class components
- Use the `.jsx`/`.tsx` extension for files containing JSX
- Destructure props in component parameters
- Use fragment shorthand (`<>...</>`) instead of `<React.Fragment>`
- For styled components, use the `.styles.js` suffix

Example:
```jsx
// Good
function UserProfile({ name, email, onUpdate }) {
  // Component logic
  return (
    <>
      <h1>{name}</h1>
      <p>{email}</p>
    </>
  );
}

// Avoid
function userprofile(props) {
  // Component logic
  return (
    <React.Fragment>
      <h1>{props.name}</h1>
      <p>{props.email}</p>
    </React.Fragment>
  );
}
```

## Python Guidelines

We follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code with these specifications:

- Use 4 spaces for indentation
- Maximum line length of 88 characters (compatible with Black formatter)
- Use snake_case for variables, functions, methods, and modules
- Use PascalCase for classes
- Use UPPER_CASE for constants
- Use docstrings (following [Google's style guide](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings))

Example:
```python
def get_representative_by_zip(zip_code, include_details=False):
    """Get list of representatives for a given ZIP code.
    
    Args:
        zip_code (str): The ZIP code to search for representatives.
        include_details (bool, optional): Whether to include detailed 
            information. Defaults to False.
            
    Returns:
        list: List of representative objects.
        
    Raises:
        ValueError: If zip_code is not a valid US ZIP code.
    """
    # Implementation
    pass
```

## CSS/Tailwind Guidelines

- Use consistent naming for CSS classes
- Prefer Tailwind utility classes over custom CSS when possible
- If custom CSS is needed, use BEM naming convention
- Keep complex interactions in JavaScript, not CSS

## File Organization

- Group related files in directories
- Use lowercase with hyphens for file and directory names
- Organize components by feature or route when possible
- Use index files to simplify imports

## Git Practices

- Write clear, descriptive commit messages
- Use present tense ("Add feature" not "Added feature")
- Reference issues in commit messages when relevant
- Keep commits focused on a single change
- Rebase feature branches before merging

## Documentation

- Document all public APIs and components
- Include examples in documentation where helpful
- Keep README and other docs up to date with code changes
- Document known limitations or edge cases

## Testing

- Write tests for all new features and bug fixes
- Aim for high test coverage, especially for critical paths
- Name tests clearly to describe what they're testing
- Use meaningful assertions that verify behavior, not implementation

Remember that this style guide is meant to help, not hinder. Readability and maintainability are our top priorities.