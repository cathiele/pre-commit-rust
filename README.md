# pre-commit hooks for rust

For general instructions see https://pre-commit.com/

## example usage

```
  - repo: https://github.com/cathiele/pre-commit-rust
    rev: v0.1.0
    hooks:
      - id: cargo-fmt
      - id: cargo-udeps
      - id: cargo-audit
      - id: cargo-check
      - id: cargo-clippy
      - id: cargo-test

```

---
**NOTES**

* ```cargo-udeps``` needs the **nightly toolchain** and ```cargo-udeps``` installed (```cargo install cargo-udeps```)
* ```cargo-audit``` needs ```cargo-audit``` installed (```cargo install cargo-audit```)

---
