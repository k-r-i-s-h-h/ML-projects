ML Projects — House Price Prediction (Day 1)
A simple, first-steps machine learning project to predict house prices from a small dataset.
This repo currently includes:
housepricing.ipynb — Jupyter notebook with the full workflow (load → explore → train → evaluate).
Book.csv — the dataset used in the notebook (tabular data with columns like area, rooms, price, etc.).
Goal: learn-by-doing using a straightforward Linear Regression baseline and build momentum for daily ML practice
What’s inside the notebook
Setup & Data Load
Reads Book.csv into a pandas DataFrame.
Exploratory Data Analysis (EDA)
Quick .info(), .describe(), null checks, and simple visuals.
Preprocessing
Selects features/target, handles missing values, basic encoding if needed.
Modeling
Trains a LinearRegression model (scikit-learn).
Evaluation
Reports metrics like MAE, RMSE, and R².
Predictions
Generates predictions and shows a few examples.
Requirements
Python 3.9+
Jupyter Notebook / JupyterLab

Common data/ML libraries:
