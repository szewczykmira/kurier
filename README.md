# kurier

Page for listing all packages in progress

# Development

Requires python >= 3.14

Works with uv

## Code quality

```shell
uv run ruff check --fix
uv run ruff format
uv run ty check
```

or enable pre-commit

```shell
pre-commit install
```

# Running project

```shell
brew services start postgresql@18
uv run ./manage.py runserver
```