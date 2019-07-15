# pytest mirror

Mirror of pylint package for pre-commit.

For pre-commit: see `https://github.com/pre-commit/pre-commit`

For pytest: see `https://pytest.org`

## Using pytest with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/szebenyib/pre-commit-pytest
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pytest
