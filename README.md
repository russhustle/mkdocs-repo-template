# MkDocs Repository Template

This is a template repository for MkDocs projects using Material theme.

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

### Installation

1. Install uv if you haven't already:

    ```bash
    pip install uv
    ```

2. Install dependencies:
    ```bash
    uv sync --extra dev
    ```

### Common Commands

-   **Serve documentation locally**:

    ```bash
    uv run mkdocs serve
    ```

-   **Build documentation**:

    ```bash
    uv run mkdocs build
    ```

-   **Run pre-commit hooks**:

    ```bash
    make pre-commit
    ```

-   **Add new dependencies**:

    ```bash
    # Add to main dependencies
    uv add package-name

    # Add to dev dependencies
    uv add --dev package-name
    ```

### Migration from Poetry

This project was migrated from Poetry to uv. The main changes:

-   Replaced `poetry.lock` with `uv.lock`
-   Updated `pyproject.toml` to use standard Python packaging format
-   Updated `Makefile` to use `uv run` instead of `poetry run`
-   Dependencies are now managed with `uv add` instead of `poetry add`
