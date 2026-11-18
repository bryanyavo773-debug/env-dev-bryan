# Aide-mémoire du terminal Linux

## Se déplacer

| Commande   | Ce qu'elle fait                    | Exemple    |
| ---------- | ---------------------------------- | ---------- |
| `pwd`      | Affiche le dossier où je suis      | `pwd`      |
| `ls`       | Affiche les fichiers et dossiers   | `ls`       |
| `ls -a`    | Affiche aussi les fichiers cachés  | `ls -a`    |
| `cd`       | Retourne dans le dossier personnel | `cd`       |
| `cd ..`    | Remonte au dossier précédent       | `cd ..`    |
| `cd ~/dev` | Entre dans le dossier dev          | `cd ~/dev` |
| `clear`    | Nettoie l'écran du terminal        | `clear`    |

## 2. Fichiers et dossiers

| Commande | Description                         | Exemple                     |
| :------- | :---------------------------------- | :-------------------------- |
| `mkdir`  | Crée un nouveau dossier             | `mkdir projet`              |
| `touch`  | Crée un fichier vide                | `touch index.html`          |
| `cp`     | Copie un fichier                    | `cp a.txt b.txt`            |
| `mv`     | Déplace ou renomme un fichier       | `mv ancien.txt nouveau.txt` |
| `rm`     | Supprime un fichier                 | `rm test.txt`               |
| `rmdir`  | Supprime un dossier vide            | `rmdir projet`              |
| `tree`   | Affiche l'arborescence des dossiers | `tree`                      |

## 3. Lire et chercher

| Commande | Description                               | Exemple                     |
| :------- | :---------------------------------------- | :-------------------------- |
| `cat`    | Affiche le contenu d'un fichier           | `cat README.md`             |
| `less`   | Affiche un fichier page par page          | `less README.md`            |
| `head`   | Affiche les premières lignes d'un fichier | `head README.md`            |
| `tail`   | Affiche les dernières lignes d'un fichier | `tail README.md`            |
| `grep`   | Recherche un mot dans un fichier          | `grep "Linux" README.md`    |
| `find`   | Recherche un fichier ou un dossier        | `find . -name "index.html"` |

## Astuce de bryan

`git log --oneline --graph` dessine l'historique avec les branches.
