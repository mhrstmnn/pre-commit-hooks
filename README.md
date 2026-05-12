# pre-commit hooks

Collection of useful pre-commit hooks

## Usage

Add the hooks you want to use to your `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/mhrstmnn/pre-commit-hooks
    rev: v0.2.0
    hooks:
      - id: ty-check
      - id: clang-format
      - id: clang-tidy
      - id: clangd-tidy
```
