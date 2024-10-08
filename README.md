# Credit-Risk-Assessment-Prediction-LightGBM-SHAP-and-Hyperopt-

This project focuses on credit risk assessment by building a default prediction model using LightGBM. It leverages Roll Rate Analysis to understand "default" and evaluates the importance of "days past due" (dpd) in credit scoring. Feature selection is performed using Random Forest and Deep Decision Trees, with Target Encoding for categorical variables.

Hyperparameter optimization is done via Hyperopt, and model evaluation metrics include ROC AUC and PR AUC. Feature importance is assessed using Split and Gain, with SHAP employed for model explainability and visualizing feature contributions. The optimal threshold is determined using the Class Rate Curve to minimize credit loss.
