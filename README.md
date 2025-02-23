# Scraping des Données Méteorologique avec R


**Projet de Web Scraping des Données Météorologiques en Tunisie**

Ce projet consiste à extraire des données météorologiques pour plusieurs villes de Tunisie à partir du site [world-weather.info](https://world-weather.info). L'objectif est de collecter des informations telles que les températures diurnes et nocturnes, les conditions météorologiques, et les précipitations pour chaque jour, mois et année, sur une période donnée.

### Fonctionnalités :
- **Web Scraping** : Utilisation du package `rvest` en R pour extraire les données météorologiques à partir des pages web.
- **Nettoyage des données** : Transformation des températures de Fahrenheit en Celsius, renommage des colonnes, et création de nouvelles colonnes pour identifier les jours de pluie.
- **Structuration des données** : Les données sont organisées dans un dataframe et exportées en format CSV pour une analyse ultérieure.
- **Visualisation** : Utilisation de `ggplot2` pour la visualisation des données météorologiques.

### Technologies utilisées :
- **R** : Langage de programmation principal pour le scraping et l'analyse des données.
- **rvest** : Package R pour le web scraping.
- **dplyr** : Pour la manipulation et la transformation des données.
- **ggplot2** : Pour la visualisation des données.
- **readr** : Pour la lecture et l'écriture de fichiers CSV.

### Structure du projet :
- **Scraping des données** : Extraction des données météorologiques pour plusieurs villes tunisiennes sur une période de 2015 à 2024.
- **Nettoyage et transformation** : Conversion des températures, renommage des colonnes, et création de nouvelles variables.
- **Export des données** : Les données nettoyées sont exportées en CSV pour une utilisation ultérieure.

### Utilisation :
1. **Installation des packages nécessaires** : 
   ```R
   install.packages(c("rvest", "dplyr", "ggplot2", "readr", "tidyr", "reshape2", "cluster"))
   ```
2. **Exécution du script** : Le script R permet de scraper les données, de les nettoyer, et de les exporter en CSV.
3. **Analyse des données** : Les données peuvent être utilisées pour des analyses statistiques, des visualisations, ou pour entraîner des modèles de prédiction météorologique.

### Exemple de données extraites :
- **Villes** : Gafsa, Kasserine, Zarzis, Tozeur, Tataouine, Jendouba, Tabarka, Béja, Sousse, Zaghouan, Tunis, Hammamet, Sfax, Jabinyanah, Skhira.
- **Période** : De janvier 2015 à décembre 2023.
- **Variables** : Température diurne, température nocturne, conditions météorologiques, précipitations.

### Contribution :
Les contributions sont les bienvenues ! Si vous souhaitez améliorer le projet, n'hésitez pas à ouvrir une issue ou à soumettre une pull request.

---

Cette description donne un aperçu clair de votre projet, des technologies utilisées, et de la manière dont les autres peuvent contribuer ou utiliser votre travail.
