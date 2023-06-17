rust(-conda) mirror
====================

Mirror of rust for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For rust: see https://github.com/rust-lang/rust

### Using ruff with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-rust
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: cargo-fmt-conda
     - id: clippy-conda
```

