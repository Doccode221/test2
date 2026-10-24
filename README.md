# Checkpoint : Flux de travail Git

Ce dépôt contient la résolution pas à pas du Checkpoint Git ainsi que quelques captures d'écran des principales étapes.

---

## 1. Initialisation et premier commit
* Création du dossier `learn_git` et déplacement dans le répertoire.
* Création du fichier `third.txt`.
* Initialisation avec `git init`.
* Ajout à la staging area et premier commit.


---

## 2. Historique et second commit
* Vérification avec `git log`.
* Création de `fourth.txt`, indexation et validation (`git commit -m "adding fourth.txt"`).


---

## 3. Suppression et mise à jour
* Suppression de `third.txt` (`rm third.txt`).
* Indexation de la modification avec `git add .`.
* Validation du retrait (`git commit -m "removing third.txt"`).
* Vérification de l'historique complet avec `git log`.


---

## 4. Configuration globale
* Configuration de l'afficheur : `git config --global core.pager cat`.
* Liste des réglages globaux : `git config --global --list`.

