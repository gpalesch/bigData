# Women's Rights

## Description du Projet

Ce projet consiste à construire un **Data Warehouse** pour analyser des statistiques liées au genre, telles que les écarts dans le marché du travail, les ratios de travail non rémunéré, et les différences de salaires entre hommes et femmes. Les données utilisées proviennent de **Kaggle** et sont traitées via des outils modernes comme **Azure**, **Databricks**, et **Apache Iceberg**.

## Objectif

- Centraliser et organiser les données sur les inégalités de genre.
- Nettoyer, transformer et stocker les données dans un modèle **Lakehouse**.
- Créer un **schéma en étoile** pour faciliter les analyses et les rapports.
- Préparer les données pour des visualisations et des analyses avancées.

## Technologies Utilisées

- **Azure** : Blob Storage et Data Lake Storage.
- **Databricks** : Apache Spark pour le traitement des données et Iceberg pour la gestion des tables.
- **Kaggle** : Source des données.
- **Parquet** et **Iceberg** : Formats de stockage des données.

## Formats et Frameworks

- **Langage** : PySpark, SQL.
- **Frameworks** :
  - Apache Iceberg pour la gestion des tables.
  - Databricks pour le traitement des données.
- **Formats de stockage** :
  - CSV pour les données brutes.
  - Parquet pour les couches Silver et Gold.
  - Delta pour la table des faits avec auto-incrémentation.
