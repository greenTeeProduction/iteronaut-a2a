# Contributing to Iteronaut A2A

Thank you for your interest in contributing to Iteronaut A2A! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

By participating in this project, you agree to abide by our code of conduct: be respectful, considerate, and collaborative.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for improvement:

1. Check if the issue already exists in the [GitHub issue tracker](https://github.com/greenTeeProduction/iteronaut-a2a/issues)
2. If not, create a new issue with a clear description, steps to reproduce, and expected vs. actual behavior

### Development Process

1. Fork the repository
2. Create a new branch for your feature or bugfix: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Run tests locally to ensure they pass: `pytest`
5. Run the linter to ensure code quality: `ruff check .`
6. Commit your changes with a descriptive commit message
   - Commit message format: `type: subject` (e.g., `feat: add new feature` or `fix: resolve issue`)
   - Types: feat, fix, docs, style, refactor, test, chore
7. Push your branch to your fork
8. Submit a pull request to the main repository

### Pull Request Guidelines

- Keep pull requests focused on addressing a single concern
- Write clear, descriptive commit messages
- Include tests for new features or bug fixes
- Update documentation as needed
- All tests must pass before a PR can be merged
- All commits must be signed with GPG

## Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/greenTeeProduction/iteronaut-a2a.git
   cd iteronaut-a2a
   ```

2. Install development dependencies:
   ```bash
   pip install -e ".[dev]"
   ```

## Code Style

This project uses Ruff for linting and follows PEP 8 guidelines. Please ensure your code passes all lint checks before submitting.

## License

By contributing to this project, you agree that your contributions will be licensed under the project's [Apache License 2.0](LICENSE).