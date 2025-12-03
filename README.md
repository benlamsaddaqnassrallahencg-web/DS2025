# Projet : Prédiction du Churn Client (Telco)

## Contenu
- `notebook_churn.ipynb` : Notebook complet (pré-traitement, EDA, modélisation, sauvegarde du modèle).
- `report.pdf` : Rapport scientifique synthétique (PDF).
- `requirements.txt` : Dépendances Python.
- `video_script.txt` : Script recommandé pour la vidéo de présentation.
- `best_model.joblib`, `scaler.joblib` : (générés après exécution du notebook).

## Instructions
1. Placer le dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` dans `/mnt/data/data/`.
2. Ouvrir et exécuter `notebook_churn.ipynb` dans Google Colab ou Jupyter.
3. Installer les dépendances : `pip install -r requirements.txt`.
4. Le notebook sauvegardera le meilleur modèle dans `/mnt/data/project_churn_output/` une fois terminé.

## Remarques
Le notebook utilise matplotlib pour les graphiques et scikit-learn pour la modélisation.
