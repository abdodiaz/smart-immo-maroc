# 🏡 Smart Immo Maroc

Smart Immo Maroc est un simulateur intelligent d’évaluation immobilière adapté au contexte marocain.  
Il permet aux utilisateurs d’estimer le **prix de vente d’un appartement** à partir de ses caractéristiques : surface, nombre de chambres, localisation, équipements, etc.

---

## 🎯 Objectif

Concevoir un **modèle de régression supervisé** entraîné sur des données réelles pour prédire le prix d’un bien immobilier.

---

## 🛠️ Fonctionnalités principales

- 🔍 Analyse exploratoire des données (EDA)
- 🧼 Prétraitement des données (nettoyage, encodage, normalisation)
- 🤖 Entraînement de plusieurs modèles (Linear Regression, Random Forest, SVR, Gradient Boosting)
- 📊 Évaluation avec MAE, RMSE, R²
- 🏆 Sélection et sauvegarde du meilleur modèle
- 📁 Intégration prévue dans une future interface web

---

## 📂 Structure du projet

```
smart-immo-maroc/
│
├── data/
│   ├── raw/              # Données brutes (CSV)
│   └── processed/        # Données nettoyées
│
├── notebooks/
│   ├── eda_preprocessing.ipynb
│   └── model_training.ipynb
│
├── models/               # Modèles enregistrés (.pkl)
├── reports/              # Rapport final
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Lancer le projet

1. Cloner le dépôt :
```bash
git clone https://github.com/ton-profil/smart-immo-maroc.git
cd smart-immo-maroc
```

2. Installer les dépendances :
```bash
pip install -r requirements.txt
```

3. Lancer le notebook d’analyse :
```bash
jupyter notebook notebooks/eda_preprocessing.ipynb
```

---

## 📋 Auteurs & encadrement

Projet réalisé par : **Abdelbarre Dazia**  
Dans le cadre de la formation IA / Data

Encadré par : *Équipe pédagogique -  Simplon*

---

## 📄 Licence

Ce projet est open source sous licence MIT.
