# API — Point d'entrée du Backend

Ce dossier contient tout le code qui gère les **requêtes HTTP** entrantes. C'est le point d'entrée de votre application.

## Rôle
- Définir les routes (endpoints) de l'API.
- Recevoir les requêtes du frontend ou d'autres services.
- Appeler la logique métier (dans `SHARED/` ou `auth/`).
- Interroger la base de données (via `DATABASE/Models/`).
- Renvoyer les réponses au format JSON.

## Organisation attendue
- **`controllers/`** : Fonctions qui traitent chaque requête.
- **`middlewares/`** : Fonctions intermédiaires (authentification, validation, logs).
- **`routes.js`** : Définition des routes et association aux contrôleurs.

## Exemple de route
```javascript
router.post('/login', authController.login);
