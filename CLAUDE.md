# CLAUDE.md - AI Assistant Guide for pengfei

This file provides context and guidelines for AI assistants (like Claude) working with this repository.

## Repository Overview

**Repository:** pengfei991112-hue/pengfei
**Status:** New project - initial setup phase
**Last Updated:** 2026-01-30

### Project Description

This repository is in its initial setup phase. Update this section with:
- Project purpose and goals
- Target users/audience
- Key features and functionality

## Codebase Structure

```
pengfei/
├── CLAUDE.md           # AI assistant guidelines (this file)
└── .git/               # Git repository
```

*Update this section as the project structure develops.*

### Planned/Recommended Structure

```
pengfei/
├── src/                # Source code
│   ├── components/     # Reusable components
│   ├── services/       # Business logic and services
│   ├── utils/          # Utility functions
│   └── index.*         # Entry point
├── tests/              # Test files
├── docs/               # Documentation
├── config/             # Configuration files
├── scripts/            # Build and utility scripts
├── CLAUDE.md           # AI assistant guidelines
├── README.md           # Project documentation
├── package.json        # Dependencies (if Node.js)
└── .gitignore          # Git ignore rules
```

## Technology Stack

*Update this section with the actual technologies used:*

- **Language:** [e.g., TypeScript, Python, Go]
- **Framework:** [e.g., React, FastAPI, Express]
- **Database:** [e.g., PostgreSQL, MongoDB, SQLite]
- **Testing:** [e.g., Jest, pytest, Go test]
- **Build Tool:** [e.g., Webpack, Vite, Make]

## Development Workflow

### Getting Started

```bash
# Clone the repository
git clone <repository-url>
cd pengfei

# Install dependencies (update based on project type)
# npm install       # Node.js
# pip install -r requirements.txt  # Python
# go mod download   # Go

# Run the development server
# npm run dev       # Node.js
# python main.py    # Python
# go run .          # Go
```

### Common Commands

| Command | Description |
|---------|-------------|
| `npm install` / `pip install -r requirements.txt` | Install dependencies |
| `npm run dev` / `python main.py` | Start development server |
| `npm test` / `pytest` | Run tests |
| `npm run build` / `make build` | Build for production |
| `npm run lint` / `flake8` | Run linter |

### Git Workflow

1. **Create feature branch:** `git checkout -b feature/your-feature-name`
2. **Make changes:** Implement your feature or fix
3. **Test:** Ensure all tests pass
4. **Commit:** Use descriptive commit messages
5. **Push:** `git push -u origin feature/your-feature-name`
6. **Create PR:** Open a pull request for review

### Commit Message Convention

Follow conventional commits format:

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

## Code Conventions

### General Guidelines

1. **Code Quality:**
   - Write clean, readable code with meaningful names
   - Keep functions small and focused (single responsibility)
   - Add comments only for non-obvious logic
   - Follow DRY (Don't Repeat Yourself) principle

2. **Error Handling:**
   - Handle errors gracefully
   - Provide meaningful error messages
   - Log errors appropriately for debugging

3. **Security:**
   - Never commit secrets or credentials
   - Validate all user inputs
   - Follow OWASP security guidelines

4. **Testing:**
   - Write tests for new features
   - Maintain test coverage
   - Test edge cases and error conditions

### File Naming Conventions

- Use consistent naming across the codebase
- Prefer kebab-case for files: `my-component.ts`
- Use PascalCase for classes/components: `MyComponent`
- Use camelCase for functions/variables: `myFunction`

## AI Assistant Guidelines

### When Working on This Repository

1. **Before Making Changes:**
   - Read and understand existing code in the affected area
   - Check for existing patterns and conventions
   - Review related tests if they exist

2. **Making Changes:**
   - Follow existing code style and patterns
   - Keep changes focused and minimal
   - Don't over-engineer solutions
   - Avoid introducing new dependencies unless necessary

3. **Code Quality:**
   - Write self-documenting code
   - Add tests for new functionality
   - Ensure linting passes
   - Handle errors appropriately

4. **Security Considerations:**
   - Never expose secrets or credentials
   - Validate inputs at system boundaries
   - Be mindful of injection vulnerabilities
   - Follow principle of least privilege

### Things to Avoid

- Don't add features beyond what's requested
- Don't refactor code unrelated to the task
- Don't add unnecessary comments or documentation
- Don't create abstractions for single-use cases
- Don't guess at requirements - ask for clarification

### Common Pitfalls

- Forgetting to handle edge cases
- Not checking for existing similar implementations
- Over-complicating simple solutions
- Missing error handling
- Not following existing patterns

## Configuration

### Environment Variables

*Update with actual environment variables as needed:*

| Variable | Description | Required | Default |
|----------|-------------|----------|---------|
| `NODE_ENV` | Environment mode | No | `development` |
| `PORT` | Server port | No | `3000` |
| `DATABASE_URL` | Database connection string | Yes | - |
| `API_KEY` | External API key | Yes | - |

### Configuration Files

- `.env` - Environment variables (not committed)
- `.env.example` - Example environment file
- `config/` - Application configuration

## Testing

### Running Tests

```bash
# Run all tests
npm test  # or pytest, go test ./...

# Run specific test file
npm test -- path/to/test  # or pytest path/to/test.py

# Run with coverage
npm test -- --coverage  # or pytest --cov
```

### Test Organization

- Unit tests: Test individual functions/components
- Integration tests: Test component interactions
- E2E tests: Test complete user flows

## Troubleshooting

### Common Issues

1. **Dependencies not installing:**
   - Clear node_modules/venv and reinstall
   - Check Node/Python version compatibility

2. **Tests failing:**
   - Ensure all dependencies are installed
   - Check for environment variables
   - Review recent changes

3. **Build errors:**
   - Check for syntax errors
   - Verify configuration files
   - Review error messages carefully

## Resources

### Documentation

- [Project README](./README.md)
- [Contributing Guide](./CONTRIBUTING.md)
- [API Documentation](./docs/api.md)

### External Resources

*Add relevant links:*
- Framework documentation
- Style guides
- Related projects

---

## Changelog

| Date | Changes |
|------|---------|
| 2026-01-30 | Initial CLAUDE.md created |

---

*This file should be updated as the project evolves. Add specific patterns, conventions, and guidelines as they are established.*
