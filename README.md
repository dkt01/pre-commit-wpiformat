# pre-commit-wpiformat
[Wpiformat](https://github.com/wpilibsuite/styleguide/tree/main/wpiformat) hook for [pre-commit](https://pre-commit.com/)

## Using wpiformat With Pre-Commit

```
-   repo: https://github.com/dkt01/pre-commit-wpiformat
    rev: main
    hooks:
    -   id: wpiformat
        args: [-clang=10]
```
