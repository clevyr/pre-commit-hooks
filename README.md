# pre-commit-hooks

This repo contains various [pre-commit](https://pre-commit.com) hooks.

## Example Usage

```yaml
repos:
  - repo: https://github.com/clevyr/pre-commit-hooks
    rev: v0.0.4
    hooks:
      - id: docker_hot_eslint
      - id: docker_hot_stylelint
      - id: docker_hot_pint
      - id: docker_hot_larastan
      - id: docker_hot_backend_test
      - id: docker_hot_vtsc
      - id: docker_hot_frontend_build
```

## Available Hooks

### docker_hot_eslint

### docker_hot_stylelint

### docker_hot_pint

### docker_hot_larastan

### docker_hot_backend_test

### docker_hot_vtsc

### docker_hot_frontend_build
