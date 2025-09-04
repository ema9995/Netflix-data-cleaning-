📊 Netflix Data Cleaning & Analysis
📌 Contexte

Ce projet a pour objectif de nettoyer et analyser un dataset lié au catalogue Netflix (films, séries, documentaires).
L’analyse permet de mieux comprendre la répartition des contenus, les tendances en fonction des pays, des années et des genres.

🗂️ Données

Source : Netflix Dataset sur Kaggle
 (ou autre selon ton projet).

Format : CSV

Contenu principal :

Title : Titre du contenu

Type : Film ou Série

Director : Réalisateur

Cast : Acteurs

Country : Pays d’origine

Date Added : Date d’ajout sur Netflix

Release Year : Année de sortie

Rating : Classification (TV-MA, PG, etc.)

Duration : Durée (minutes ou saisons)

Listed In : Genres

Description : Résumé du contenu

🧹 Étapes de nettoyage (Data Cleaning)

Gestion des valeurs manquantes (ex. pays, réalisateur, cast).

Uniformisation des formats de dates.

Séparation des colonnes multi-valeurs (ex. genres, pays).

Transformation des colonnes numériques (durée en minutes, nombre de saisons).

Vérification des doublons.

⚙️ Technologies utilisées

Python 🐍

Pandas : nettoyage et transformation des données
