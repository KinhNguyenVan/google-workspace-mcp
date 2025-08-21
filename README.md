# Using uv in this Project

This project supports [uv](https://github.com/astral-sh/uv), a fast Python package manager and runner.

## Install dependencies

If you have a `pyproject.toml` file:

```sh
uv pip install -r pyproject.toml
```

Or, if you have a `requirements.txt` file:

```sh
uv pip install -r requirements.txt
```

## Run a Python script

For example, to run the server:

```sh
uv python src/mcp_google_sheets/server.py
```

## Add a new package

```sh
uv pip install <package-name>
```

This will update your lock file (e.g., `uv.lock`).
