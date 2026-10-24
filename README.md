# git-pre-commit
Configuration files to set up git pre-commit hooks.

## Get started
```bash
# pip
pip install pre-commit
pre-commit install

# uv
uv add pre-commit
uv run pre-commit install

# init
uv run pre-commit sample-config > .pre-commit-config.yaml

# run
uv run pre-commit run --all-files
```
