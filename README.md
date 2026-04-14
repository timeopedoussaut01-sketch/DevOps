\# TP DevOps - Gestion Git



\## Installation de Git

Installation effectuée sur Windows Powershell. Commande de vérification :

```bash

git --version

Les sources utilisés :

Documentation officielle Git -> Pour les commandes.
Guide GitHub - Connexion SSH -> Pour la génération de la clé

Lexique des commandes Utilisées :

git branch	-> Permet d'isoler le développement sur une branche develop sans impacter le code stable.
git checkout	-> Utilisé pour naviguer entre les branches main et develop.
git commit -m	-> Enregistre un "instantané" (snapshot) des modifications avec un message explicatif.
git merge	-> Fusionne les travaux validés de la branche develop vers la branche main.
git push origin	-> Synchronise les commits locaux vers le serveur distant GitHub.
New-Item	-> Utilisé pour créer les fichiers de test (file1, file2, file3).
Remove-Item	-> Utilisé pour nettoyer le projet en supprimant file3.
