# MKDocs Repo Template

[![GitHub stars](https://img.shields.io/github/stars/russhustle/mkdocs-repo-template.svg)](https://github.com/russhustle/mkdocs-repo-template/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Documentation Status](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://russhustle.github.io/mkdocs-repo-template/)

A clean and customizable template for creating documentation sites with MkDocs and the Material theme.

## Features

-   Pre-configured Material theme with dark/light mode switching
-   Mathematics support via MathJax for LaTeX equations
-   Enhanced styling with custom CSS for lists and text elements
-   Code presentation with syntax highlighting and snippets functionality
-   Content management with auto-generated last modification dates
-   Continuous deployment through GitHub Actions workflows
-   Code quality enforcement via pre-commit hooks
-   Dependency management with Poetry

Perfect starting point for technical documentation, project wikis, or knowledge bases with minimal setup required.

## Getting Started

### Installation

```bash
# Clone this repository
git clone https://github.com/russhustle/mkdocs-repo-template.git
cd mkdocs-repo-template

# Install dependencies with Poetry
poetry install
```

### Local Development

```bash
# Start the development server
poetry run mkdocs serve
```

Your documentation site will be available at `http://localhost:8000`.

### Building the Site

```bash
# Build the static site
poetry run mkdocs build
```

The built site will be in the `site/` directory.

## Customization

Edit `mkdocs.yml` to configure your site settings, navigation, and theme options.

## Code Snippets Example

```python title="demo-snippets.py" linenums="1"
--8<-- "demo-snippets.py"
```

## Mathematics Example

MathJax renders LaTeX equations beautifully:

$$
E = mc^2
$$

## Contributing

Contributions are welcome!
