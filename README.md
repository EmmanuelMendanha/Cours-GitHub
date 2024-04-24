# Cours GIT & GitHub 


Git est un logiciel de versioning, qui permet de gerer plus efficacemnt le developpement d'une application.

## Les principes de base de Git

 - Travailler sur une branche : Le travail dans une application s'effectue toujours sur une branche dediee a la fonctionnalite que l'on souhaite developper.
 - Ne pas travailler sur la branche master : La branche master est la branche principale de l'application, elle doit rester propre et stable.
 - Toujours tirer avant de coder : `git pull` est indispensable pour recuperer les dernieres modifications de la branche sur laquelle on travaille.
 - Enrengistrer avec un message clair : `git commit -m "message"` permet de sauvegarder les modifications effectuees. Prenez le soin de rédiger un message clair et concis.

## Les commandes de base de Git

| Commande | Description |
| --- | --- |
| `git init` | Initialise un depot git |
| `git clone` | Clone un depot git |
| `git status` | Affiche l'etat du depot |
| `git add` | Ajoute un fichier a l'index |
| `git commit` | Enregistre les modifications |
| `git remote` | Gere les depots distants |
| `git push` | Envoie les modifications sur le depot distant |
| `git pull` | Recupere les modifications du depot distant |
| `git branch` | Gere les branches |
| `git merge` | Fusionne les branches |

Il existe differente options (flags) pour chaque commande, en fonction de l'action que vous souhaitez effectuer.

## GitHub

GitHub est un service en ligne qui permet d'heberger des projets git. Il permet de partager son code, de travailler en collaboration et de gerer les problemes (bugs, ameliorations, etc...).

## Les principes de base de GitHub

- Priorité au dépôt local : GitHub est un service en ligne, il est donc important de toujours travailler en local et de pousser son code sur GitHub.
- Limiter les modifications directes sur GitHub : Les modifications directes sur GitHub sont à éviter, elles peuvent entraîner des conflits et des pertes de code.
- Sécuriser son compte : Activez la double authentification pour sécuriser votre compte et ainsi éviter les intrusions.
- Nommer des collaborateurs : Pour travailler en collaboration, il est important de nommer des collaborateurs sur un dépôt.
- Établisser des règles : Il est important de définir des règles de contribution pour que le travail en collaboration se passe bien.