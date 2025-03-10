---
title: Machine Learning Superivsed
publishDate: 2019-10-02 00:00:00
img: /portfolio/assets/cap-titanic-app2.png
img_alt: image titanic app
description: |
  🚢 Prédire la survie sur le Titanic avec un modèle KNN : quand les données historiques rencontrent l'intelligence artificielle. 🤖
tags:
  - JavaScript
  - JupyterLab
  - API Flask
---

### Création et conception:

> Vous pouvez accéder au site en cliquant sur le lien suivant, <a href="https://mimiecmoua.github.io/titanic-survival-test/">"Titanic Survival Test"</a>.

### Projet : Prédiction de survie au naufrage du Titanic 🚢

Ce projet est une application web interactive qui prédit si un passager du Titanic aurait survécu au naufrage en fonction de son âge, de sa classe et de son sexe. L'application utilise un modèle de machine learning supervisé, une API Flask, et une interface front-end développée avec Bootstrap et JavaScript.

### Fonctionnalités principales 🌟

- **Prédiction en temps réel** : L'utilisateur peut saisir des informations (classe, sexe, âge) et obtenir une prédiction de survie.
- **Interface utilisateur intuitive** : Une interface simple et responsive conçue avec Bootstrap.
- **API Flask** : Une API backend qui gère les prédictions en utilisant un modèle de machine learning.
- **Déploiement** : L'application est déployée sur GitHub Pages, et l'API est hébergée sur Render avec UptimeRobot pour surveiller la disponibilité.

### Technologies utilisées 💻

- **Machine Learning** : Modèle de classification K-Nearest Neighbors (KNN) avec `scikit-learn`.
- **Backend** : API Flask pour servir le modèle de prédiction.
- **Frontend** : HTML, CSS (Bootstrap), et JavaScript pour l'interface utilisateur.
- **Déploiement** :
  - Frontend : GitHub Pages.
  - Backend : Render avec UptimeRobot pour la surveillance.

### Étapes du projet 🛠️

1. **Collecte des données** :

   - J'ai utilisé les données réelles du registre des passagers du Titanic pour entraîner le modèle.

2. **Création du modèle** :

   - J'ai développé un modèle de classification KNN avec `scikit-learn` pour prédire la survie.
   - Le modèle prend en entrée la classe, le sexe et l'âge du passager.

3. **Développement de l'API** :

   - J'ai créé une API Flask pour servir le modèle. L'API reçoit les données du frontend et renvoie la prédiction.
   - Testée avec Postman et le navigateur.

4. **Interface utilisateur** :

   - J'ai conçu une interface simple avec Bootstrap pour permettre à l'utilisateur de saisir les informations.
   - La communication entre le frontend et l'API est gérée avec `fetch`.

5. **Déploiement** :
   - Le frontend est déployé sur GitHub Pages.
   - L'API est hébergée sur Render, avec UptimeRobot pour surveiller la disponibilité.

### Code clé 🔑

```python
from sklearn.neighbors import KNeighborsClassifier
import numpy as np

def survie(model, pclass=1, sex=1, age=15):
    x = np.array([pclass, sex, age]).reshape(1, 3)
    return model.predict(x)

```

> Besoin d'une projet IA innovant ?
> Écrivez-moi !

```

```
