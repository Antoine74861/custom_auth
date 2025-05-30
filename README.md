# custom\_auth

A small Python package to store and easily access credentials.

> [!WARNING]
> Passwords are stored in plain text in a `.py` file. This is not secure, but quick to set up for simple local use.

## Installation

```bash
pip install git+https://github.com/Antoine74861/custom_auth.git
```

## Location

To find the location of the package and edit the credentials, use:

```bash
pip show custom_auth
```

The path shown in `Location` contains `custom_auth/db.py`, which you can modify as needed.

## Usage

```python
from custom_auth import DB_PASSWORD

print(DB_PASSWORD)
```

## Uninstallation

```bash
pip uninstall custom_auth
```
