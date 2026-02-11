# Contributing to TruSteward

Thank you for your interest in contributing to TruSteward! This document provides guidelines and instructions for contributing.

## Development Setup

1. Fork and clone the repository
2. Run `.scripts/setup-dev.sh` to set up the development environment
3. Run `make dev` to start the development environment
4. Run `make test` to run tests

## Code Style

### Rust
- Follow the Rust style guide
- Run `cargo fmt` before committing
- Run `cargo clippy` to check for common issues
- Document all public APIs

### Go
- Use `go fmt` to format code
- Follow the standard Go conventions
- Run `go vet` before committing

### Python
- Use Black for formatting (line length 88)
- Use type hints for all functions
- Follow PEP 8 conventions
- Run `ruff check` and `mypy` before committing

## Pull Request Process

1. Create a feature branch from develop
2. Make your changes with tests
3. Ensure all tests pass
4. Update documentation if needed
5. Create a pull request

## Security

- Never commit secrets or keys
- Report security issues to security@truesteward.io
- Follow secure coding practices

## License

By contributing, you agree that your contributions will be licensed under the Apache 2.0 license.
