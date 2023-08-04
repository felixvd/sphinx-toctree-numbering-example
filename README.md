# Sphinx numbering issues with multiple doc trees

A minimal example to demonstrate Sphinx section numbering issues when multiple ToCs include the same file:

![sphinx-toc-numbering-problem.png](sphinx-toc-numbering-problem.png)


## Setup

```
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade sphinx sphinx-rtd-theme
```


## Build

```
make manual1
make manual2
```


## References

- [Allow including documents multiple times (using different section numbers)](https://github.com/sphinx-doc/sphinx/issues/10744)
