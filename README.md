# Spotify_Project

Ce repository contient mon projet Spotify ....


## Installation

1. Cloner le repository

```bash
git clone https://github.com/Marjorie-J/Spotify_Project.git
cd Spotify_Project
```

2. Créer un environnement

```bash
python -m venv spotify_env
source spotify_env/bin/activate
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
└── Spotify_Project/
    ├── datas/
    ├── src/
    ├── .gitignore
    ├── README.md
    └── requirements.txt