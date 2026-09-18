# auth — Authentification et sécurité

Ce dossier est dédié à la **sécurité** et à la **gestion des identités**. Il est séparé pour bien isoler cette logique critique.

## Rôle
- Gérer la **connexion** et la **déconnexion**.
- Gérer les **sessions** (JWT).
- Hacher les mots de passe (bcrypt).
- Vérifier les **rôles** (Admin, Coach, Parent, Employé, Responsable).
- Bloquer les accès non autorisés.

## Contenu attendu
- **`login.js`** : Fonction de connexion.
- **`logout.js`** : Fonction de déconnexion.
- **`middleware_auth.js`** : Vérifie que l'utilisateur est connecté.
- **`roles.js`** : Définition des rôles et permissions.

## ⚠️ Règles de sécurité
- **Ne jamais stocker un mot de passe en clair.** Utilisez `bcrypt`.
- **Ne jamais commiter de clé secrète** (JWT secret, clé API). Utilisez des variables d'environnement (`.env`).
- **Toujours valider les entrées** de l'utilisateur avant de les traiter.
