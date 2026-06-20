# 📦 StockMaster Pro — Logiciel de gestion de stock

Application de bureau développée en Python pour gérer l'inventaire, les ventes et les statistiques d'un petit commerce (ex: boutique en ligne).

## Fonctionnalités

- **Gestion de l'inventaire** : ajout, modification et suppression de produits (référence, nom, catégorie, quantité, prix)
- **Recherche et filtrage** par catégorie de produit
- **Suivi des ventes** avec statistiques associées
- **Alertes de stock** : seuils critique et préventif configurables pour anticiper les ruptures
- **Export automatique vers Excel** des données d'inventaire (via openpyxl)
- **Interface graphique** complète avec navigation par onglets (Inventaire / Catégories / Ventes)

## Technologies utilisées

- **Python**
- **Tkinter** (interface graphique)
- **openpyxl** (export et lecture de fichiers Excel)

## Lancer le projet

```bash
pip install openpyxl
python Code_Projet_Gestion.py
```

## Contexte

Projet personnel réalisé pour mettre en pratique mes bases en programmation Python, dans le cadre de ma réorientation vers un BTS Services Informatiques aux Organisations (SIO).

## Pistes d'amélioration

- Ajouter une base de données (SQLite) à la place du fichier Excel
- Ajouter une gestion des utilisateurs / droits d'accès
- Tests unitaires
