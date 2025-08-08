# FooFighters_Project

L’évolution du style musical des Foo Fighters

Objectif :
Étudier l’évolution musicale des Foo Fighters à travers le temps en analysant les audio features fournies par Spotify.


## Installation

1. Cloner le repository

```bash
git clone https://github.com/Marjorie-J/FooFighters_Project.git
cd FooFighters_Project
```

2. Créer un environnement

```bash
python -m venv ff_env
source ff_env/bin/activate
```

3. Installer les dépendances

```bash
pip install -r requirements.txt
```


## Configuration des variables d'environnement

1. Créer un fichier `secret.sh` à la racine du projet

```bash
export SPOTIFY_CLIENT_ID="votre-client-id"
export SPOTIFY_CLIENT_SECRET="votre-client-secret"
```

2. Charger les variables d'environnement

```bash
source secret.sh
```


## Structure du Repository

```
.
└── FooFighters_Project/
    ├── datas/
    ├── src/
    ├── .gitignore
    ├── README.md
    └── requirements.txt