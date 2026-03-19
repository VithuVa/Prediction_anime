# M.R.R. Project 2025 : Prédiction de Popularité d'Anime & Recommandation

**Auteurs :** Arnaud GRASSIAN & Vithuson VAITHILINGAM 
**Date :** Décembre 2025

## Description du Projet

Ce projet s'inscrit dans le cadre du cours M.R.R. 2025. L'objectif est d'exploiter un jeu de données issu de Kaggle (MyAnimeList ) pour répondre à deux problématiques principales :

1.  **Prédiction (Régression) :** Est-il possible de prédire la note moyenne (*score*) d'un anime en fonction de ses caractéristiques (genre, studio, staff, etc.) ?
2.  **Recommandation (Classification) :** Comment sélectionner des utilisateurs spécifiques pour leur recommander de nouveaux animes (prédiction binaire "Aimé" / "Pas Aimé") ?

##Prérequis Techniques

Pour exécuter ce projet, vous avez besoin de **R** et **RStudio**. Les scripts sont au format R Markdown (`.Rmd`).

### Packages R nécessaires
Le code dépend des librairies suivantes. Assurez-vous de les installer via la commande `install.packages()` :

```r
install.packages(c("data.table", "dplyr", "glmnet", "caret", "formatR", "knitr"))
