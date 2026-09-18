# Migrations

Ce dossier contient les scripts qui modifient la **structure** de la base de données.

## Rôle
- Créer, modifier ou supprimer des tables et des colonnes.
- Versionner l'évolution de la base de données dans le temps.

## Convention de nommage
Exemple : `20260919_create_users_table.sql`

## Règles
- **Une migration ne doit jamais être modifiée après avoir été exécutée** sur la base de données commune.
- Si vous devez corriger une erreur, créez une **nouvelle** migration.
- Testez toujours votre migration en local avant de la pousser.
