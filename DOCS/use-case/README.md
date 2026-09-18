# Use Cases

Ce dossier contient les **spécifications fonctionnelles** du projet, rédigées sous forme de Use Cases.

## Rôle
- Décrire une interaction complète entre un acteur et le système.
- Servir de référence pour le développement et la validation.
- Permettre de lier une Pull Request à une spécification.

## Convention de nommage
Exemple : `UC-01-connexion.md`, `UC-02-gestion-presences.md`

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
