# Prédiction de la Pollution Atmosphérique  
**Projet de Machine Learning – Régression**


[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.5-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

Résumé
-------
Ce dépôt contient un pipeline complet pour la prédiction de la pollution atmosphérique : ingestion et prétraitement des données, entraînement et sélection de modèles de régression, évaluation et inférence. L'objectif principal est de prédire des concentrations de polluants (ex. PM2.5, PM10, O3) à partir de données météorologiques, temporelles et d'observations locales.

Quickstart
----------
1. Cloner le dépôt
   git clone https://github.com/YUZMV/Air-pollution-prediction.git
2. Créer un environnement Python 3.9+
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
3. Installer les dépendances
   pip install -r requirements.txt
4. Placer vos données dans data/ (voir section Données)
5. Lancer l'entraînement (exemple)
   python src/train.py --config config/train.yaml
