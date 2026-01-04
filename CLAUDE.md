# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build and Run Commands

```bash
uv run main.py          # Run the application
uv sync                 # Install dependencies from pyproject.toml
uv add <package>        # Add a dependency
uv add --dev <package>  # Add a dev dependency
```

## Testing

```bash
uv run pytest                    # Run all tests
uv run pytest tests/test_foo.py  # Run a single test file
uv run pytest -k "test_name"     # Run tests matching a pattern
```

## Linting and Formatting

```bash
uv run ruff check .     # Lint code
uv run ruff format .    # Format code
```

## Project Structure

- Python 3.10+ project managed with uv
- Entry point: `main.py`
- Dependencies defined in `pyproject.toml`
