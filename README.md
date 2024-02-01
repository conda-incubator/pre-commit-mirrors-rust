# rust pre-commit hook

pre-commit hook of rust with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For rust: see [here](https://github.com/rust-lang/rust)

## Using rust with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-rust
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: rust-conda
```
