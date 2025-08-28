# Data-Science-Project
# Supplier Selection and Performance Analysis (MSc Project)

This repository contains my MSc Data Science project on supplier selection and performance evaluation using both **TOPSIS** (MCDM) and **Machine Learning** (Logistic Regression, Random Forest, XGBoost).

#Note
For a quick overview, please run only "FinalSupplier_Performance_Data_Science_Project" 
The other notebooks (01 → 06) show the development stages.

## Project Aim
Compare interpretable decision ranking (TOPSIS) with predictive ML models for supplier performance, and deliver a reproducible, end-to-end workflow.

## Repository Structure
- `code/01_data_cleaning.ipynb` — preprocessing (dates, missing values, numeric types)
- `code/02_feature_engineering.ipynb` — KPIs: Cost_Savings, Delivery_Duration, Defect_Rate_Percent
- `code/03_topsis_ranking.ipynb` — TOPSIS ranking (weights: 0.4, 0.3, 0.3; impacts: +, –, –)
- `code/04_ml_models.ipynb` — Logistic Regression, Random Forest, XGBoost (fixed split)
- `code/05_results_analysis.ipynb` — confusion matrices, ML vs TOPSIS visual comparisons
- `code/06_deployment_pipeline.ipynb` — load `.pkl` model, score new data, export predictions
- `code/FinalSupplier_Performance_Data_Science_Project` — clean, reproducible end-to-end pipeline for 

## How to Run
1. Open in **Google Colab** (or Jupyter).
2. Provide the input CSV (supplier dataset).
3. Run in order: 01 → 02 → 03 → 04 → 05 → 06.  
   For a quick demo, run `code/Final_Project.ipynb` only.

## Requirements
`pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`



## Author
Oladayo Blessing Oladeji — MSc Data Science
