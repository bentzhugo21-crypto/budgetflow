# 💸 BudgetFlow

Application web de **budget personnel automatique**. Vous entrez votre salaire, définissez une répartition par catégorie, suivez vos dépenses, votre épargne et vos objectifs.

## Fonctionnalités

- **Répartition automatique** du salaire par catégorie (en pourcentages)
- **Budget dynamique** : un salaire différent de l'habituel redistribue le surplus selon une règle au choix (proportionnel, vers l'épargne, ou personnalisé)
- **Tableau de bord** mensuel avec navigation et **archivage automatique des mois précédents**
- **« Combien puis-je dépenser aujourd'hui ? »** — budget restant ÷ jours avant la paie
- **Prélèvements automatiques** (loyer, factures…) pré-remplis chaque mois
- **Objectifs** (ex. voyage au Japon) alimentés automatiquement par une catégorie
- **Épargne** : suivi de différents supports (Livret A, assurance-vie, ETF…), alimentés automatiquement
- **Alertes & conseils** sur les budgets dépassés

## Technique

- Un seul fichier : `index.html` (HTML + CSS + JavaScript, sans dépendance)
- Les données sont stockées **localement dans le navigateur** (`localStorage`) — privées, sur votre appareil
- Aucune installation, aucun serveur : il suffit d'ouvrir le fichier

## Utilisation

Ouvrez `index.html` dans un navigateur, ou consultez la version en ligne (GitHub Pages).
