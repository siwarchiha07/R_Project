# 📊 Analyse Statistique des Développeurs GitHub Influents

Ce projet propose une étude approfondie de la popularité des développeurs et organisations les plus suivis sur GitHub. À l'aide du langage **R** et de l'écosystème **Quarto**, nous analysons les facteurs qui influencent le nombre d'étoiles (*stars*) récoltées, tels que les langages de programmation utilisés, la localisation géographique et le type de compte (individuel vs organisation).

## 🎯 Objectifs du Projet

L'analyse répond à 5 questions de recherche fondamentales :
1. **Distribution de la popularité** : Comment les étoiles sont-elles réparties parmi l'élite de GitHub ?
2. **Individus vs Organisations** : Les comptes institutionnels (OpenAI, Google) dominent-ils les développeurs solo ?
3. **Analyse Géographique** : Quelles régions du monde concentrent le plus d'influence Open Source ?
4. **Impact Technologique** : Le choix d'un langage (Python, JS, C++) a-t-il un impact statistique sur le succès ?
5. **Volume de contribution** : Existe-t-il une corrélation entre le nombre de dépôts créés et la popularité totale ?

## 📁 Structure du Répertoire

- `profiles_index.csv` : Le jeu de données brut contenant 30 profils GitHub majeurs.
- `01-analyse-profiles-github.qmd` : Le fichier source Quarto contenant le code R et les interprétations.
- `Examen_R.ipynb` : Notebook de travail utilisé pour l'exploration initiale sur Google Colab.
- `rapport.html` : Le rapport final généré (visualisable dans un navigateur).

## 🛠️ Technologies Utilisées

- **Langage** : R (v4.0+)
- **Bibliothèques** :
  - `tidyverse` (dplyr, ggplot2, readr) : Manipulation et visualisation de données.
  - `wordcloud` : Génération de nuages de mots pour les langages.
  - `knitr` : Moteur de rendu de documents.
- **Reporting** : Quarto



