# DOCS — Documentation du projet

Ce dossier contient toute la **documentation non technique** : spécifications, Use Cases, guides, schémas.

## Rôle
- Centraliser les spécifications fonctionnelles.
- Permettre aux professeurs et aux élèves de comprendre le projet sans lire le code.
- Servir de référence pour les Pull Requests (lier le code à la spécification).

## Contenu
- **`use-case/`** : Fichiers Markdown décrivant chaque Use Case.
- *(à venir)* `architecture/` : Schémas de l'architecture technique.
- *(à venir)* `guides/` : Guides d'installation, de déploiement, etc.

## Règles
- Tout Use Case doit être rédigé en **Markdown**.
- Les diagrammes doivent utiliser **Mermaid** (recommandé) ou Draw.io (avec fichier source).
- **Interdit** : photos de dessins, fichiers `.docx` ou `.pdf`.

- Exemple : `UC-01-connexion.md`, `UC-02-gestion-presences.md`

## Structure d'un Use Case
1. **Acteur principal** : Qui utilise la fonctionnalité ?
2. **Objectif** : Que veut-il faire ?
3. **Préconditions** : Que faut-il avant de commencer ?
4. **Scénario nominal** : Les étapes normales.
5. **Scénarios alternatifs** : Les cas d'erreur ou exceptions.
6. **Postconditions** : L'état du système après l'action.

## Règle de regroupement
- **Un Use Case = Un parcours utilisateur complet**, pas une micro-action.
- ✅ `[Responsable] Consulter les chiffres et gérer les fournisseurs`
- ❌ `Cliquer sur le bouton "Voir les chiffres"`
