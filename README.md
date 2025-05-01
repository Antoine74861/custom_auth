# custom_auth

Un petit package Python pour stocker et accéder facilement à des identifiants.

> ⚠️ Les mots de passe sont stockés en clair dans un fichier `.py`. Ce n’est pas sécurisé, mais rapide à mettre en place pour un usage local simple.

## Installation
```bash
pip install git+https://github.com/Antoine74861/custom_auth.git
```

## Localisation
Pour connaître l’emplacement du package et modifier les identifiants, ouvrir le fichier `db.py` :
```bash
pip show custom_auth
```

Le chemin affiché dans `Location` contient `custom_auth/db.py`, à modifier selon les besoins.

## Usage
```python
from custom_auth import DB_PASSWORD

print(DB_PASSWORD)
```

## Désinstallation
```bash
pip uninstall custom_auth
```
