# TP DevOps - Gestion Git

## Gestion Git
Installation effectuée sur Windows. Commande de vérification :

```PowerShell
## 1. Introduction

Ce projet à pour but de mettre en place une gestion de version structurée pour un projet de développement

## 2. Installation de Git

git --version

## 3. Sources utilisées : 

Documentation officielle Git -> Pour les commandes (https://git-scm.com/doc)
Guide GitHub - Connexion SSH -> Pour la génération de la clé (https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

## 4. Lexique des commandes utilisées :

git branch	-> Permet de isoler le développement sur une branche develop sans impacter le code stable.
git checkout	-> Utilisé pour naviguer entre les branches main et develop.
git commit -m	-> Enregistre un "instantané" (snapshot) des modifications avec un message explicatif.
git merge	-> Fusionne les travaux validés de la branche develop vers la branche main.
git push origin	-> Synchronise les commits locaux vers le serveur distant GitHub.
New-Item	-> Utilisé pour créer les fichiers de test (file1, file2, file3).
Remove-Item	-> Utilisé pour nettoyer le projet en supprimant file3.

## 5. Lexique des commandes utilisées :

graph LR
    A[Initialisation] --> B(Branche develop)
    B --> C{Modifs}
    C --> D[Merge]
    D --> E[Branche main]