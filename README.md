
# DS230 Final Project – Instacart Reorder Prediction (Fall 2025)

## Project Overview
This project is part of the DS230 course final project.  
The goal is to analyze Instacart shopping history data and build predictive models for:

- **Task A (Classification):** Predict whether a product will be reordered by a user in their next order.
- **Task B (Regression):** Predict the number of days until a user's next order.

The project follows a full end-to-end data science workflow including data preprocessing, feature engineering, model training, evaluation, explainability, and robustness testing.

---

## Dataset
The project uses the **Instacart Market Basket Analysis** dataset, which consists of multiple relational files:

- orders.csv  
- order_products_prior.csv  
- products.csv  
- aisles.csv  
- departments.csv  

All data ingestion, joins, and preprocessing are performed programmatically using Python.

---

## Project Structure

- 01_Data Loading & Initial EDA.ipynb
- 02_Extended EDA and Preprocessing.ipynb
- 03_feature_engineering.ipynb
- 04_taskA_classification.ipynb
- 05_taskB_regression.ipynb
- 06_models_comparison.ipynb
- 07_explainability_SHAP.ipynb
- 08_robustness_tests.ipynb
- 09_model_interpretability.ipynb  
- 10_Final__Summary_&_Reflection.ipynb
- data/ (dataset files not included) 


---

## Notebook Description

### 01_Data Loading & Initial EDA.ipynb
- Loads all raw Instacart datasets
- Performs memory-efficient joins
- Basic cleaning and data type optimization

### 02_Extended EDA and Preprocessing.ipynb
- Exploratory Data Analysis (EDA)
- Missing value analysis
- Distribution plots and correlation analysis
- Temporal patterns (day of week, hour of day)

###  03_feature_engineering.ipynb
- User-level, product-level, and user-product interaction features
- Temporal and frequency-based features
- Target construction for both tasks
- Creation of the final modeling dataset

### 04_taskA_classification.ipynb
- Binary classification task (reorder prediction)
- Models implemented:
  - Logistic Regression
  - KNN Classifier
  - SVM (Linear)
  - Decision Tree
  - Random Forest
- Evaluation using Accuracy, Precision, Recall, F1-score, ROC-AUC

### 05_taskB_regression.ipynb
- Regression task (days until next order)
- Models implemented:
  - Linear Regression (Lasso, Ridge, ElasticNet)
  - KNN Regressor
  - SVR
  - Decision Tree Regressor
  - Random Forest Regressor
  - LightGBM Regressor
- Evaluation using MAE, RMSE, and R²

### 06_models_comparison.ipynb
- Comparison of all models across tasks
- Summary tables and visual comparisons
- Discussion of model strengths and weaknesses

### 07_explainability_SHAP.ipynb
- Model interpretability using SHAP
- Feature importance analysis
- Local and global explanations for predictions

### 08_robustness_tests.ipynb
- Model stability under:
  - Added Gaussian noise
  - Reduced training data
- Analysis of performance degradation

### 09_model_interpretability.ipynb 
- Interactive visualizations using Plotly
- Actual vs predicted comparisons
- Model performance visual summaries

---

## Reproducibility
- All experiments use fixed random seeds.
- Intermediate datasets are saved and reused across notebooks.
- The project is designed to run on Google Colab.

---

## Requirements
Main Python libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lightgbm
- shap
- plotly

---

## Authors
- Student 1: [Lara malkawi] , id [184401 ]
- Student 2: [Jana shloul] , id [184386]

Both team members contributed to data preprocessing, modeling, and analysis.

---

## Notes
Some models (e.g., Random Forest and SVR) were trained using sampled data to reduce memory usage and runtime while preserving meaningful results.




