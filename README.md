📊 Walmart Weekly Sales Forecasting

This project builds a machine learning model to predict weekly sales for Walmart stores using historical data. The final model is based on CatBoost Regressor, combined with strong feature engineering and log-transformation, achieving highly accurate and stable predictions.

🚀 Project Overview

Preprocessed and cleaned Walmart sales dataset

Extracted features from date (Day, Month, Year)

Applied log-transform on Weekly Sales

One-hot encoded Store feature

Detected and removed outliers

Trained ML models: Linear Regression, LightGBM, XGBoost, CatBoost

Performed hyperparameter tuning using RandomizedSearchCV

Evaluated on train, test, and unseen data

📈 Model Performance
Train Dataset
R²: 0.9923
RMSE: 49,294
MAE: 32,171

Test Dataset
R²: 0.9892
RMSE: 59,186
MAE: 39,032

Unseen Dataset
R²: 0.9886
RMSE: 51,427
MAE: 33,544

➡️ The model achieves ~5% error, making it suitable for real-world forecasting.

🛠️ Technology Stack
Python
Pandas, NumPy
Scikit-Learn
CatBoost
Matplotlib, Seaborn
Google Colab / Jupyter Notebook
