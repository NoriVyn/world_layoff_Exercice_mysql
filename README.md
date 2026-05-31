# 📉 Projet : Nettoyage de Données - World Layoffs (Tech)

## 📌 Présentation du Projet
Ce projet consiste à nettoyer et préparer un dataset brut recensant les licenciements 
dans les entreprises de la Tech à travers le monde. L'objectif était de rendre la base 
de données exploitable pour une future analyse (PowerBI / Excel).

## 🛠️ Outils utilisés
- **Base de données :** MySQL (via MySQL Workbench)
- **Dataset source :** Fichier CSV des licenciements mondiaux (Tech)

## 🧽 Étapes clés du nettoyage (Data Cleaning)
1. **Création d'une table de staging** pour préserver les données brutes d'origine.
2. **Identification et suppression des doublons** via l'utilisation de `ROW_NUMBER()`.
3. **Standardisation des données :** Correction des anomalies textuelles (ex: uniformisation des pays avec `LIKE`, nettoyage des espaces avec `TRIM`).
4. **Conversion des types :** Transformation des formats textuels en vraies dates SQL avec `STR_TO_DATE`.
5. **Gestion des valeurs manquantes :** Traitement des cases vides et conversion en valeurs `NULL`.

## 💡 Compétences SQL démontrées
- Jointures complexes (`INNER JOIN` pour correction de données)
- Fonctions de fenêtrage (`Window Functions` : `ROW_NUMBER() OVER()`)
- Logique conditionnelle (`CASE WHEN`, `COALESCE`)
- Requêtes de modification (`UPDATE`, `ALTER TABLE`)
