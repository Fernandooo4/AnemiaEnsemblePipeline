# AnemiaEnsemblePipeline

Repositorio con un pipeline completo para la predicción multiclase de anemia usando modelos de *stacking* y técnicas duales de remuestreo (**SMOTE-Tomek** y **SMOTE-ENN**).

## 🧠 Algoritmos usados
- LightGBM
- XGBoost
- CatBoost
- TabNet
- Random Forest
- Decision Tree
  

## ⚙️ Técnicas de balanceo aplicadas
- Stacked Ensemble
- Evaluación con métricas: Accuracy, F1-Score, AUC-ROC, MCC
- Balanceo de datos con SMOTE-Tomek y SMOTE-ENN

## 📁 Estructura del repositorio
├── MBase_Smote+TOMEK/ # Resultados con bases balanceadas mediante SMOTE-Tomek
│ ├── AnemiaTipos.csv # Dataset principal
│ ├── CatBoost_SMOTETomek.ipynb # Entrenamiento y evaluación con CatBoost
│ ├── DecisionTree_SMOTETomek.ipynb # Entrenamiento y evaluación con Árbol de Decisión
│ ├── LightGBM_SMOTETomek.ipynb # Entrenamiento y evaluación con LightGBM
│ ├── RandomForest_SMOTETomek.ipynb # Entrenamiento y evaluación con Random Forest
│ ├── TabNet_SMOTETomek.ipynb # Entrenamiento y evaluación con TabNet
│ ├── XGBoost_SMOTETomek.ipynb # Entrenamiento y evaluación con XGBoost
│ └── Stacking_SmoteTomek/ # Carpeta con resultados y métricas del modelo Stacking
├── MBase_Smote-ENN/ # Resultados con bases balanceadas mediante SMOTE-ENN
│ ├── AnemiaTipos.csv # Dataset principal
│ ├── CatBoost_SMOTEENN.ipynb # Entrenamiento y evaluación con CatBoost
│ ├── DecisionTree_SMOTEENN.ipynb # Árbol de Decisión
│ ├── LightGBM_SMOTEENN.ipynb # LightGBM
│ ├── RandomForest_SMOTEENN.ipynb # Random Forest
│ ├── TabNet_SMOTEENN.ipynb # TabNet
│ ├── XGBoost_SMOTEENN.ipynb # XGBoost
│ └── Stacking_SmoteENN/ # Resultados y métricas del modelo Stacking

## 📊 Resultados destacados
SMOTE-Tomek alcanzó el mejor desempeño cuando se utilizó en conjunto con el modelo stacking cuyo meta-modelo fue TabNet

 

