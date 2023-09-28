CO2 Emissions Prediction with Hyperparameter Tuning and SHAP Analysis
This repository contains a Jupyter Notebook that demonstrates how to predict CO2 emissions from vehicles using various features like engine size, fuel consumption, etc. The project uses a machine learning pipeline that includes preprocessing steps and an XGBoost model.

Key Features:
Data Preprocessing: The notebook includes different preprocessing steps for numerical and categorical features.

Hyperparameter Tuning: Optuna is used for hyperparameter optimization of the XGBoost model.

Model Evaluation: The model is evaluated using k-fold cross-validation.

Interpretability: SHAP (SHapley Additive exPlanations) is used to interpret the model's predictions. This gives insights into which features are most important for predicting CO2 emissions.

Technologies Used:
Python
scikit-learn
XGBoost
Optuna
SHAP
