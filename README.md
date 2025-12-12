# Analyse des ventes de pizzas avec SQL & Power BI

Ce projet présente un dashboard interactif d’analyse des ventes de pizzas, construit à partir d’un dataset réel-like comprenant environ 48 000 lignes de commandes sur une année. L’objectif est d’aider un restaurant à comprendre ses performances commerciales, les habitudes d’achat de ses clients et à identifier les meilleures et pires pizzas.

## Objectifs du projet

- Calculer les KPIs clés :
  - Chiffre d’affaires total
  - Valeur moyenne par commande
  - Nombre total de pizzas vendues
  - Nombre total de commandes
  - Nombre moyen de pizzas par commande
- Analyser :
  - Les tendances journalières et mensuelles des commandes
  - La répartition des ventes par catégorie de pizza et par taille
  - Les jours et créneaux horaires les plus chargés
  - Les Top 5 et Bottom 5 pizzas par chiffre d’affaires, quantité et nombre de commandes

## Stack technique

- **Base de données** : MS SQL Server
- **Langage requêtes** : SQL
- **BI & DataViz** : Power BI Desktop
- **Source de données** : fichier CSV de ventes de pizzas (2015)

## Étapes principales

1. Import du fichier CSV dans SQL Server et modélisation de la base (`pizza_sales`).
2. Écriture de requêtes SQL pour répondre aux besoins métiers (KPIs, tendances, tops/bottoms).
3. Connexion de Power BI à SQL Server.
4. Nettoyage et transformation des données via Power Query.
5. Création des mesures DAX (revenu, moyenne par commande, etc.).
6. Conception de deux dashboards :
   - **Dashboard 1** : KPIs, tendances journalières/mensuelles, répartition par catégorie et taille, jours/horaires les plus chargés.
   - **Dashboard 2** : Top 5 / Bottom 5 pizzas par revenu, quantité et nombre de commandes.

## Fonctionnalités du dashboard

- Filtres par catégorie de pizza et par période de dates.
- Navigation entre pages via des boutons (Home / Best & Worst Sellers).
- Visuels interactifs (clic sur un jour, une catégorie ou une taille pour filtrer tout le rapport).
- Palette de couleurs adaptée au thème pizzeria (rouge, vert, jaune, beige, etc.).
- Textes d’insights synthétiques intégrés sous les graphiques.

## Résultats clés (exemples)

- La catégorie **Classic** contribue au maximum des ventes et des commandes.
- Les pizzas de taille **Large** génèrent la plus grande part du chiffre d’affaires.
- Les commandes sont les plus élevées le week-end, surtout les soirs de vendredi et samedi.
- Identification des pizzas best-sellers et underperformers pour guider les décisions marketing (promotions, retrait de produits, etc.).

## Auteur

Projet réalisé par **Ahmed MAKHLOUFI**, Data Analyst / BI Developer Junior.  
N’hésite pas à me contacter sur LinkedIn : Ahmed MAKHLOUFI.
