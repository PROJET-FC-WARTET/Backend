
---

### 📁 Dossier `DATABASE/Procedures/`
**Chemin :** `DATABASE/Procedures/README.md`

```markdown
# Procedures

Ce dossier contient les **procédures stockées** (stored procedures) ou les fonctions SQL complexes.

## Rôle
- Exécuter des opérations lourdes directement dans la base de données.
- Éviter de transporter trop de données entre le serveur et la base.
- Centraliser des calculs répétitifs (ex: statistiques, classements).

## Convention de nommage
Exemple : `calculer_statistiques_mensuelles.sql`

## Quand utiliser une procédure ?
- Pour des agrégations complexes (sommes, moyennes, classements).
- Pour des opérations qui touchent plusieurs tables en une seule transaction.
- **Ne pas abuser** : la logique métier doit rester dans le code quand c'est possible.
