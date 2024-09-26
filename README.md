# degree# Degrees of Separation

## Description

Ce projet permet de trouver le chemin le plus court entre deux acteurs dans une base de données de films, en utilisant le concept de "degrés de séparation". Il utilise une approche de recherche en largeur (BFS) pour déterminer combien de films relient deux personnes.

## Fonctionnalités

- Chargement de données à partir de fichiers CSV.
- Recherche du chemin le plus court entre deux acteurs.
- Affichage des films dans lesquels les acteurs ont collaboré.

## Structure du Projet

/degrees/ degrees.py # Fichier principal contenant le code /util/ # Dossier contenant les classes utilitaires init.py # Fichier d'initialisation du module util.py # Contient les classes Node, StackFrontier, et QueueFrontier /large/ # Dossier contenant les fichiers CSV de données people.csv # Liste des personnes avec leurs identifiants movies.csv # Liste des films avec leurs identifiants stars.csv # Relations entre les acteurs et les films

bash
Copy code

## Installation

1. Clone le dépôt :

   ```bash
   git clone https://github.com/ton_nom_utilisateur/degrees.git
   cd degrees
Assure-toi d'avoir Python 3 installé sur ta machine.

Vérifie que tu as les fichiers CSV dans le dossier /large.

Utilisation
Pour exécuter le programme, utilise la commande suivante dans le terminal :

bash
Copy code
python3 degrees.py large
Tu seras invité à entrer le nom de deux acteurs. Par exemple :

makefile
Copy code
Name: Lauren Bacall
Name: Fred Astaire
Le programme affichera le nombre de degrés de séparation et les films dans lesquels les acteurs ont collaboré, s'ils sont connectés.

Contribuer
Si tu souhaites contribuer à ce projet, n'hésite pas à ouvrir des issues ou à soumettre des pull requests.

Acknowledgements
Ce projet est inspiré par le jeu "Six Degrees of Kevin Bacon", qui consiste à relier les acteurs entre eux par le biais des films.
License
Ce projet est sous licence MIT. Consulte le fichier LICENSE pour plus de détails.

markdown
Copy code

### Instructions

1. **Personnalise le README** : Remplace `ton_nom_utilisateur` par ton nom d'utilisateur GitHub.
2. **Crée le fichier `README.md`** dans la racine de ton projet et colle-y ce contenu.
3. **Ajoute, commit et pousse** le fichier vers ton dépôt GitHub.

Si tu as besoin d'autres modifications ou ajouts, fais-le moi savoir !
