# data_visualization_research

Neural-XGBoost with SHAP for Disaster Prediction

Project Overview

This project implements a hybrid machine learning model (Neural-XGBoost) for disaster prediction using real-world data. The model combines:

Neural Networks for deep feature extraction
XGBoost for classification
SMOTE for handling class imbalance
SHAP for model interpretability

The system predicts disaster types such as Flood, Wildfire, and Earthquake and explains the predictions using Explainable AI.

Key Features

Hybrid deep learning + boosting model
Handles missing data & class imbalance
Extracts high-level deep features
Provides high accuracy (~94–95%)
Includes SHAP explainability
End-to-end pipeline implementation

Model Architecture

Dataset → Preprocessing → Neural Network (Feature Extraction)
        → SMOTE (Balancing) → XGBoost (Classification)
        → SHAP (Explainability) → Results


🛠️ Technologies Used

Python
Pandas, NumPy
Scikit-learn
PyTorch
XGBoost
imbalanced-learn (SMOTE)
SHAP
Matplotlib