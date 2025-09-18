# Urban-Traffic-Analysis-Prediction
📈 Projet de Science des Données : Prédiction du Trafic Urbain 🏙️

# Contexte du projet

L'objectif de ce projet était d'analyser les données de trafic d'une ville pour **construire un modèle capable de prédire le nombre de véhicules** à un instant T. Ce projet met en évidence les compétences en matière de **nettoyage de données**, d'**analyse exploratoire**, de **modélisation prédictive** et d'**interprétation des résultats**.

 🚀 Méthodologie et Étapes Clés

Le projet a été mené en suivant une approche structurée en quatre étapes, de la donnée brute à la conclusion finale.

1.  **Préparation des Données :**
    -   Conversion des formats de date et d'heure.
    -   Application du One-Hot Encoding pour les données de localisation des capteurs.
    -   Création d'une variable binaire pour les heures de pointe (`Peak_Off_Peak_Encoded`).

2.  **Analyse Exploratoire (EDA) :**
    -   Visualisation des tendances de trafic par heure.
    -   Analyse de la corrélation entre la vitesse et la congestion.

3.  **Modélisation :**
    -   Construction d'un modèle de régression avec l'algorithme **Random Forest**.
    -   Le modèle a été entraîné sur 80% des données et testé sur les 20% restants.
    -   **Résultats d'évaluation :** Le modèle a atteint un score **R² de 0.96** et un **MAE de 3.2** (à confirmer avec vos valeurs exactes). 

4.  **Interprétation du Modèle :**
    -   Analyse de l'importance des variables pour comprendre les facteurs clés de la prédiction.
  
5.  **Visulaization Tableau :**
   -  J'ai synthétisé les conclusions de l'analyse et les performances du modèle en tableaux clairs et concis. Cette approche a permis de communiquer les indicateurs clés

 🎯 Résultats et Conclusions

L'analyse de l'importance des variables a clairement mis en évidence les facteurs les plus influents sur la prédiction du trafic.

> "L'importance de la vitesse du véhicule est de **0.63**, ce qui en fait le facteur le plus déterminant. Le niveau de congestion est le deuxième facteur le plus important. Cela confirme que le modèle s'appuie sur les indicateurs de fluidité pour anticiper le volume de trafic."


# Prochaines Étapes et Améliorations Possibles

* Intégrer des données externes (météo, jours fériés, événements spéciaux).
* Tester d'autres algorithmes de Machine Learning (e.g., Gradient Boosting).
* Optimiser les hyperparamètres du modèle pour une meilleure performance.

# Fichiers du Projet

* `notebooks/` : Contient les notebooks Jupyter pour chaque étape.
* `data/` : Contient les jeux de données d'entrée et de sortie.
* `images/` : Contient les graphiques générés.
* `src/` : Scripts Python autonomes.
* "![Importance des variables](images/Importance des variables pour la prédiction du trafic.png)"
* Lien Tableau:https://public.tableau.com/app/profile/adnane.ben.ammar/vizzes
