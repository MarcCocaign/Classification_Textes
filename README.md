# Analyse de textes : Hugo vs Zola

## 📌 Description

Ce projet consiste à analyser et comparer deux œuvres littéraires françaises (Victor Hugo et Émile Zola) à l’aide de techniques de traitement du langage naturel (NLP) et de machine learning.

L’objectif est de mettre en évidence les différences lexicales entre les deux auteurs et de construire un modèle de classification capable de les distinguer.

## Contenu

* `Classification_Textes.ipynb` : notebook principal contenant :

  * Prétraitement du texte
  * Analyse fréquentielle des mots
  * Calcul TF-IDF
  * Visualisation (barplots, nuages de mots)
  * Modèle de classification (Logistic Regression)

* `corpus/` : textes sources (Hugo et Zola)

## Méthodes utilisées

* Nettoyage et tokenisation des textes
* Suppression des stopwords (français)
* TF-IDF (scikit-learn)
* WordCloud et visualisations matplotlib
* Classification supervisée avec régression logistique

## Résultats

Le modèle obtient une performance élevée (≈ 97–98% d’accuracy) dans la classification des textes entre Hugo et Zola.
