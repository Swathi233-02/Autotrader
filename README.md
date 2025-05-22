# Autotrader
End-to-end ML pipeline for predicting car prices using a real-world AutoTrader dataset. Covers data cleaning, feature engineering, dimensionality reduction, model selection, ensembling, and evaluation. Developed for the Advanced Machine Learning course at MMU.

# Car Price Prediction – Advanced Machine Learning Project

This project is part of the **Advanced Machine Learning** course (6G7V0017) at Manchester Metropolitan University. It involves building a complete regression pipeline using a real-world dataset provided by AutoTrader to predict car selling prices based on vehicle features.

## Project Structure

- `AMLFinal.ipynb` – Jupyter notebook containing the full ML workflow
- `AML_Final_Report.pdf` – Structured report summarizing methodology and results

## Dataset

- Real-world dataset from AutoTrader (approx. 400,000 car sale adverts)
- Features include brand, model, mileage, fuel type, transmission, and more
- Due to licensing, the dataset is not included in this repository

## Machine Learning Pipeline

The pipeline includes:

1. **Data Preprocessing**
   - Handling missing values and outliers
   - Target encoding for high-cardinality categorical features
   - Scaling numeric data with `MinMaxScaler`

2. **Feature Engineering**
   - Polynomial features and interaction terms

3. **Dimensionality Reduction**
   - Principal Component Analysis (PCA)

4. **Model Training & Selection**
   - Linear Regression, Decision Tree, Random Forest
   - GridSearchCV for hyperparameter tuning
   - Ensemble methods

5. **Evaluation**
   - Metrics: RMSE, MAE, R²
   - Cross-validation and prediction error plots

## Results

- Best model achieved high accuracy in predicting car prices
- Feature importance and residual analysis provided valuable insights

## Disclaimer

The dataset used is proprietary and cannot be shared or redistributed. This project is for academic purposes only.

## Course Info

- **Module:** 6G7V0017 – Advanced Machine Learning  
- **Instructor:** Luciano Gerber  
- **University:** Manchester Metropolitan University  
- **Semester:** 23/24 Semester 2

---

