# Static Analysis (Backend Services - FastAPI)

This repository currently contains no Python source files, so static analysis will not report code findings yet.
The configuration below is provided so checks can be enabled immediately when code is added.

## Tools
- Ruff (lint + import sorting)
- MyPy (type checking)

## Install (example)
Depending on your environment, you may install:

```bash
python -m pip install ruff mypy
```

## Run
From the repo root:

```bash
ruff check .
mypy .
```

## Notes
- Ruff config: `pyproject.toml`
- MyPy config: `mypy.ini`
- Once FastAPI code is added, consider enabling stricter MyPy settings and adding formatting (e.g., `ruff format`) if desired.
"""
