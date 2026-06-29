EV Battery Health Prediction

Project Overview

End-to-end machine learning project to predict electric vehicle battery health using NASA Battery Dataset.

Dataset

Source: NASA Battery Dataset
7,000+ CSV files with sensor measurements
Metadata with battery test information
Data Preprocessing

Merged metadata and sensor data across 7,000+ CSV files
Handled MATLAB format inconsistencies in datetime columns
Removed columns with over 74% missing values
Aggregated 7M+ rows by battery ID using statistical features (mean, min, max, std)
Applied battery-level train/test split to prevent group leakage
Model

Algorithm: XGBoost Regressor
R² Score: 0.62
MAE: 0.159
Note: Initial model showed R² = 0.99 due to data leakage (discharge time used as feature). Fixed by removing leaky features and using proper group-based train/test split — ensuring the model generalizes to unseen batteries.
Dashboard


Dashboard
(https://public.tableau.com/app/profile/emre.kaya8517/viz/Book1_17827468515620/Dashboard1?publish=yes&showOnboarding=true)

Tech Stack
Python, Pandas, Scikit-learn, Tableau
