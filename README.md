# Iteronaut A2A

[![ci/lint-test](https://github.com/greenTeeProduction/iteronaut-a2a/actions/workflows/ci.yml/badge.svg)](https://github.com/greenTeeProduction/iteronaut-a2a/actions/workflows/ci.yml)

Iteronaut A2A (Automation-to-Automation) is a framework for building reliable pipelines between automated systems. This repository is the core implementation of the Iteronaut A2A framework.

## Features

- CI/CD integration with GitHub Actions
- Linting with Ruff
- Testing with pytest
- Security scanning with Trivy
- GPG-signed commits for security
- Pre-commit hooks for code quality

## Development

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/greenTeeProduction/iteronaut-a2a.git
   cd iteronaut-a2a
   ```

2. Install dependencies:
   ```bash
   pip install -e ".[dev]"
   ```

3. Install pre-commit hooks:
   ```bash
   pip install pre-commit
   pre-commit install --install-hooks
   ```

### Testing

Run tests using pytest:
```bash
pytest
```

### Linting

Lint the codebase using Ruff:
```bash
ruff check .
```

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.