# Python-For-Data-Science-Project
Projet de programmation de 2ème Année à L'ENSAE portant sur l'impact des risques d'inondations sur le prix de l'immobilier.

## Objectif du Projet
L'objectif principal est d'évaluer comment les risques d'inondation influencent les prix de l'immobilier en France. En combinant des données géographiques sur les zones à risque et des données transactionnelles immobilières, le projet vise à identifier des corrélations significatives et à fournir des visualisations claires de ces relations.

## Structure du Répertoire
Le répertoire est organisé en plusieurs dossiers et fichiers principaux :

. DVF Processing/ : Scripts pour le traitement des données des "Demandes de Valeurs Foncières" (DVF).

Shapefile processing/ : Scripts pour le traitement des fichiers shapefile contenant des données géographiques.

[lien](https://github.com/Jeanjacob20/Python-For-Data-Science-Project/tree/main/TRI%20API%20Processing%20) : Scripts pour l'extraction et le traitement des données via l'API des Territoires à Risque d'Inondation (TRI).

TRI Shapefile Processing/ : Scripts pour le traitement des shapefiles spécifiques aux zones TRI.

API_Valeur_fonciere.ipynb : Notebook Jupyter pour l'extraction des données foncières via une API dédiée.

Calcul des prix en euro constant.ipynb : Notebook pour l'ajustement des prix immobiliers en euros constants, en tenant compte de l'inflation.

INSEE_inflation.xlsx : Données de l'INSEE sur l'inflation, utilisées pour ajuster les prix.

Visualisation.ipynb : Notebook contenant des visualisations des données traitées, illustrant l'impact des risques d'inondation sur les prix immobiliers.

carte_risques_nature_legende.html : Carte interactive illustrant les zones à risque naturel, notamment les inondations, avec une légende détaillée.

final_dataframe.csv : Jeu de données final consolidé, résultant des différentes étapes de traitement et d'analyse.

Instructions pour l'Exécution
Prérequis : Assurez-vous d'avoir Python installé, ainsi que les bibliothèques nécessaires telles que pandas, geopandas, requests, et matplotlib.

Installation des dépendances : Utilisez pip pour installer les bibliothèques requises :

bash
Copy code
pip install pandas geopandas requests matplotlib
Exécution des scripts : Suivez l'ordre logique des notebooks et scripts pour reproduire l'analyse :

Extraction des données via les API.

Traitement et nettoyage des données.

Analyse et visualisation des résultats.

## Contributeurs
Jean JACOB,
Félix DE GUERRE,
Sofiene TAAMOUTI
