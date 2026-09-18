# SHARED — Code réutilisable

Ce dossier contient les fonctions, classes ou constantes **utilisées par plusieurs parties** de l'application.

## Rôle
- Éviter la duplication de code.
- Centraliser les utilitaires communs.
- Faciliter la maintenance (un seul endroit à modifier).

## Exemples de contenu
- **`utils.js`** : Fonctions utilitaires (formatage de date, validation d'email).
- **`constants.js`** : Constantes globales (rôles, statuts, codes d'erreur).
- **`validators.js`** : Fonctions de validation (email, mot de passe, etc.).
- **`logger.js`** : Système de journalisation des erreurs.

## Règle
> Si une fonction est utilisée dans **plus d'un dossier** (`API/`, `auth/`, `DATABASE/`), elle doit être placée ici.
