# Trustably Docs

This repository contains the documentation for Trustably, built using [MkDocs](https://mkdocs.org/).

## Local Development

### Prerequisites

Ensure you have Python installed. It is recommended to use a virtual environment.

```bash
# Create a virtual environment
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Building and Serving Locally

To build the documentation and preview it locally with live reloading:

```bash
# Build the site
mkdocs build

# Serve the site locally with live reload
mkdocs serve --livereload
```

The site will be available at `http://127.0.0.1:8000`.

## Deployment

The documentation is deployed to GitHub Pages. To deploy the latest version:

```bash
# Deploy to GitHub Pages

mkdocs gh-deploy
```

## Repository

GitHub: [git@github.com:ayanguha/trustably-docs.git](https://github.com/ayanguha/trustably-docs)

## To Do

- Github Action to deploy to pages automatically (Low Priority task)