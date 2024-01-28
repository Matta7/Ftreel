# Projet .NET : FTreeL

<!-- TOC -->
- [Projet .NET : FTreeL](#projet-net--ftreel)
  - [Groupe](#groupe)
  - [Lancement](#lancement)
<!-- TOC -->

## Groupe

Ce projet est réalisé en binôme avec :
- MERRE Alexandre
- LOVICOURT Léo
- GUERRIER Sébastien
- ELIE Jordan
- VALLÉE Mathieu

## Lancement

Il faut tout d'abord avoir Docker Desktop, ou un moyen de faire docker compose.
Il faut ensuite lancer les commandes suivantes :

- docker compose build
- docker compose up

Cela lancera dans le même conteneur la base de données et le serveur SMTP local.

Pour lancer l'API :
- dotnet ef database update
- dotnet run

Pour lancer le client :
- npm install npm run dev

Il y a 2 utilisateurs par défaut dans notre application :
- admin@ftreel.com qui a pour mot de passe admin.
- user@ftreel.com qui a pour mot de passe user
