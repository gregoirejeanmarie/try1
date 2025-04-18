# 🧠 EMG Finger Regression – Random Forest Model

Ce projet vise à prédire la position articulaire de la main (51 angles de jointure) à partir de signaux EMG multi-canaux (8 électrodes), en utilisant des modèles de régression machine learning.

## 📁 Structure des fichiers

## ⚙️ Entraînement

Le modèle utilise :
- `RandomForestRegressor` encapsulé dans `MultiOutputRegressor`
- Extraction de features sur 5 sessions
- Réduction temporaire de données pour test rapide (modifiable)

### 📈 Métriques utilisées
- MAE (Mean Absolute Error)
- R² (Score de régression)
- Visualisation : vraies vs prédictions sur 51 articulations

## 🚀 Lancer l'entraînement

```bash
# Si Python et dépendances sont installés :
python train_model.py

