# automobile-resale-ml
End-to-end ML system for automobile resale price prediction with explainability and monitoring

# Automobile Resale Price Intelligence Platform

An end-to-end machine learning system for predicting automobile resale prices with:
- Feature engineering
- Explainable AI (SHAP)
- MLflow experiment tracking
- Data & prediction drift monitoring using Evidently

## Business Problem
Used-car marketplaces and OEMs require accurate resale pricing to optimize:
- Inventory valuation
- Pricing strategy
- Risk management

## Solution Overview
This project builds a production-grade ML pipeline that:
- Predicts resale price
- Explains predictions using SHAP
- Monitors drift using Evidently dashboards
- Tracks experiments using MLflow

- ## Model Performance
- MAE: ~2.5K
- R²: ~0.90+

## Tech Stack
- Python
- Scikit-learn
- SHAP
- MLflow
- Evidently
- Pandas, NumPy, Matplotlib

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook


