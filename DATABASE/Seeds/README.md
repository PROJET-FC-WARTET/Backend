# Seeds

Ce dossier contient les scripts qui **remplissent** la base de données avec des données de test.

## Rôle
- Permettre aux élèves de travailler sur une base fonctionnelle sans attendre les vraies données du club.
- Faciliter les tests (utilisateurs fictifs, articles de stock, matchs, etc.).

## Convention de nommage
Exemple : `seed_users.sql`, `seed_stock.sql`

## Règles
- Les données de test doivent être **réalistes mais fictives**.
- **Jamais de vraies données personnelles** (noms, adresses, emails réels).
- Les seeds doivent pouvoir être exécutés plusieurs fois sans créer de doublons (utilisez `INSERT ... ON CONFLICT DO NOTHING`).
