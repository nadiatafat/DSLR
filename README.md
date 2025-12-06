# DSLR
Data Science × Logistic Regression — Hogwarts

Création d'un **classificateur multi-classes** capable de prédire la maison de chaque élève à Hogwarts en utilisant **la régression logistique**.

---

## Objectifs

* Lire et analyser les datasets (`dataset_train.csv` et `dataset_test.csv`)
* Explorer les données avec des visualisations (histogrammes, scatter plots, pair plots)
* Implémenter **une régression logistique one-vs-rest** avec **gradient descent**
* Produire un fichier `houses.csv` avec les prédictions pour le test set
* Bonus : explorer d’autres optimisations ou améliorations

---

## Fonctionnalités principales

* **Data Analysis** → `describe.py` pour résumer les features
* **Data Visualization** → histogrammes, scatter plots et pair plots
* **Logistic Regression** → entraînement et prédiction multi-classes

---

## Note

* Les fonctions de visualisation et statistiques sont implémentées **manuellement**, sans utiliser de fonctions faites pour le calcul (count, mean, std, min, max, percentile, describe, etc.)
* La précision minimale pour le modèle obligatoire : **98% sur le test set**
