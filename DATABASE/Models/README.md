# Models

Ce dossier contient les **classes ou fichiers** qui représentent les tables de la base de données dans le code.

## Rôle
- Définir les champs d'une table (email, mot de passe, rôle, etc.).
- Définir les relations entre les tables (ex: un Coach a plusieurs équipes).
- Fournir des méthodes pour interagir avec la table (ex: `User.findByEmail()`).

## Convention de nommage
- Un fichier par table.
- Nom du fichier au **singulier** et en **PascalCase** : `User.js`, `Presence.js`, `StockItem.js`.

## Exemple
```javascript
class User {
  constructor(id, email, password, role) {
    this.id = id;
    this.email = email;
    this.password = password;
    this.role = role;
  }
}
