# pre-commit hooks for rust

For general instructions see https://pre-commit.com/

## example usage

```
  - repo: https://github.com/cathiele/pre-commit-rust
    rev: v0.1.0
    hooks:
      - id: cargo-fmt
      - id: cargo-udep
      - id: cargo-audit
      - id: cargo-check
      - id: cargo-clippy
      - id: cargo-test

```

---
**NOTES**

* ```cargo-udep``` needs the **nightly toolchain** and ```cargo-udep``` installed (```cargo install cargo-udep```)
* ```cargo-audit``` needs ```cargo-audit``` installed (```cargo install cargo-audit```)

---
