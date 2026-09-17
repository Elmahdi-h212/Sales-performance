# Power BI — Sales Performance Dashboard

Analyse des performances commerciales à partir d'un jeu de données retail nettoyé avec Power Query et analysé avec DAX.

## Projet

Ce projet présente un dashboard Power BI permettant de suivre les ventes selon :
- l'année
- la région / ville
- la catégorie
- le client
- l'évolution mensuelle

## Workflow

**Raw Data → Power Query → Data Model → DAX → Dashboard → Insights**

## KPI

- Total Sales
- Total Orders
- Average Order Value
- Total Quantity
- Total Customers

## Nettoyage des données

Le fichier original contient des problèmes de qualité volontairement présents dans le dataset. Le nettoyage a été réalisé dans Power Query :
- correction des types de données
- traitement des valeurs manquantes
- remplacement des villes manquantes par `Inconnu`
- Trim / Clean des champs texte
- suppression des doublons

Voir [`Documentation/Data_Quality.md`](Documentation/Data_Quality.md).

## DAX

Les mesures principales sont disponibles dans [`DAX/Measures.md`](DAX/Measures.md).

## Insights

Les principaux constats sont disponibles dans [`Documentation/Insights.md`](Documentation/Insights.md).

## Données

Le fichier source original est conservé dans :

`Data/PowerBI_Messy_Retail_Project-1.xlsx`

## Dashboard

Ajoutez ici le fichier `.pbix` du projet Power BI ainsi que les captures finales du dashboard si nécessaire.
