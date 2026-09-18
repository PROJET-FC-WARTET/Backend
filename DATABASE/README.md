
---

### 📁 Dossier `DATABASE/`
**Chemin :** `DATABASE/README.md`

```markdown
# DATABASE — Persistance des données

Ce dossier centralise tout ce qui touche à la **base de données** : structure, accès, données de test.

## Rôle
- Versionner l'évolution de la base de données.
- Séparer la logique de données du reste de l'application.
- Permettre à plusieurs élèves de travailler sur la base sans conflit.

## Contenu
- **`Migrations/`** : Scripts qui modifient la structure (création de tables, colonnes).
- **`Models/`** : Représentation des tables dans le code (ex: `User.js`).
- **`Procedures/`** : Procédures stockées SQL.
- **`Seeds/`** : Scripts pour remplir la base avec des données de test.

## Règles importantes
- **Ne jamais modifier une migration déjà exécutée en production.** Créez-en une nouvelle.
- **Ne jamais commiter de données sensibles** (mots de passe réels, données personnelles).
- Les noms de tables et de colonnes doivent être en **anglais** (convention).
