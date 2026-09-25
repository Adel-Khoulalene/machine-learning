# 🍷 Wine Quality Classification

> Un projet d'analyse exploratoire et de Machine Learning pour prédire la qualité du vin en fonction de ses caractéristiques physico-chimiques.

## 📝 Description

Ce projet utilise une approche orientée données pour modéliser l'expertise œnologique. À l'aide de Python, de Pandas et de Scikit-Learn, nous analysons un jeu de données de vins pour en extraire les variables clés (acidité, taux de sucre, pH, alcool, etc.) et entraînons un modèle prédictif basé sur l'algorithme **Random Forest**.

## 🛠️ Technologies Utilisées

- **Langage** : Python 3
- **Manipulation de données** : Pandas, NumPy
- **Machine Learning** : Scikit-Learn (RandomForestClassifier)
- **Visualisation** : Matplotlib, Seaborn
- **Environnement** : Jupyter Notebook

## ⚙️ Installation et Exécution

### 1. Cloner le dépôt
```bash
git clone [https://github.com/Adel-Khoulalene/machine-learning.git](https://github.com/Adel-Khoulalene/machine-learning.git)
cd machine-learning
```
### 2. Créer un environnement virtuel (recommandé)
```bash
python -m venv env
source env/bin/activate  # Sur Windows : env\Scripts\activate
```

### 3. Installer les dépendances
```bash
pip install -r requirements.txt
```

### 4. Lancer le notebook
```bash
jupyter notebook
```

## 📊 Structure du projet
dataset_wine.csv : Le jeu de données brut utilisé pour l'entraînement.

notebook_analyse.ipynb : Le notebook contenant l'Analyse Exploratoire des Données (EDA), le prétraitement et l'entraînement du modèle.

requirements.txt : La liste des librairies Python nécessaires.

## 🚀 Améliorations futures (Roadmap)
[ ] Interface Web Streamlit : Création d'une application web app.py intégrant un file_uploader permettant d'analyser n'importe quel fichier CSV avec une gestion flexible des délimiteurs et des formats de dates.

[ ] Agent Data Analytics : Intégration d'un assistant conversationnel via LangChain et l'API Groq (avec des modèles comme llama-3.3-70b-versatile) pour permettre d'interroger les prédictions et les données du vin en langage naturel.

[ ] Déploiement : Hébergement de l'application sur Streamlit Cloud pour la rendre accessible publiquement
