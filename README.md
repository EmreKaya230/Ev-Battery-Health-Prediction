# EV Battery Health Prediction

## Project Overview
End-to-end machine learning project to predict electric vehicle battery health 
using NASA Battery Dataset.

## Dataset
Source: [NASA Battery Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset)
7,000+ CSV files with sensor measurements
Metadata with battery test information

## Data Preprocessing
Merged metadata and sensor data across 7,000+ CSV files
Handled MATLAB format inconsistencies in datetime columns
Removed columns with 74%+ missing values
Aggregated 7M+ rows by battery ID using group mean

## Model
Algorithm: Random Forest Regressor
R² Score: 0.99
MAE: 0.014

## Dashboard
[Tableau Public Dashboard](https://public.tableau.com/app/profile/emre.kaya8517/viz/EV_Battery_Health_Analysis/Dashboard1)

## Tech Stack
- Python, Pandas, Scikit-learn, Tableau
