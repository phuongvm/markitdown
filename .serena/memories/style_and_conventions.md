# Style and Conventions

## Code Style
- **Formatting**: The project uses `black` for code formatting. Ensure all code is formatted before committing.
- **Type Hints**: Type hints are used throughout the codebase. `mypy` is used for type checking.
- **Docstrings**: Public functions and classes should have clear docstrings.

## Structure
- New converters should be added to `packages/markitdown/src/markitdown/converters`.
- They should inherit from `_base_converter.BaseConverter` (or similar).
- Tests should be added to `packages/markitdown/tests`.

## Contribution
- Sign the CLA if required.
- Run tests and pre-commit checks before PR.
