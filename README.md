# Extreme Values — Analyse statistique des précipitations extrêmes

## Présentation du projet

Projet universitaire réalisé en binôme dans le cadre d'un Travail d'Étude et de Recherche (TER), consacré à la **théorie des valeurs extrêmes (Extreme Value Theory — EVT)**.

L'objectif est d'étudier les événements météorologiques rares et de modéliser les précipitations extrêmes afin d'estimer les risques associés à des épisodes pluvieux exceptionnels.

## Données étudiées

L'analyse repose sur les données de précipitations journalières de la station météorologique de **Saint-Maurice-Navacelles**, issues de Météo-France.

- **Période :** 1950–2024 (75 ans)
- **Observations :** 27 277 mesures journalières
- **Variable étudiée :** hauteur quotidienne des précipitations (mm)
- **Précipitation maximale observée :** 375 mm en une journée

## Méthodes statistiques

Plusieurs approches de la théorie des valeurs extrêmes ont été étudiées et appliquées :

- **Block Maxima (GEV) :** modélisation des maxima annuels par une loi des valeurs extrêmes généralisée.
- **Peaks Over Threshold (GPD) :** analyse des précipitations dépassant un seuil élevé, fixé à 50 mm, avec prise en compte de la dépendance temporelle par déclustering.
- **Estimateur de Hill :** étude de l'indice de queue de distribution.
- **Diagnostics graphiques :** QQ-plots, Mean Excess Plots et graphiques de stabilité pour évaluer les ajustements.

## Principaux résultats

Les modèles GEV et GPD ont permis d'estimer les niveaux de retour associés aux événements pluvieux rares.

Pour une période de retour de 100 ans :

- **Modèle GEV :** environ 317 mm
- **Modèle GPD :** environ 470 mm

Ces différences mettent en évidence la sensibilité des estimations au modèle statistique choisi et l'incertitude associée à l'étude d'événements très rares.

## Technologies et compétences

- **R / R Markdown**
- Analyse statistique et exploration de données
- Modélisation probabiliste (GEV, GPD)
- Estimation de paramètres et quantiles extrêmes
- Visualisation et interprétation de résultats

## Auteurs

Projet réalisé par **Baptiste Pyryt et Gaspard Teston** dans un cadre universitaire.
