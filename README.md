
# DS230 Final Project – Instacart Reorder Prediction

This project analyzes Instacart shopping history to predict product
reorders and time-to-next-order. The workflow follows a complete
machine learning pipeline including data preprocessing, feature
engineering, supervised modeling, evaluation, robustness testing,
and interpretability analysis.

---

## Project Objectives

- Perform full exploratory data analysis and preprocessing
- Engineer user-level, product-level, and user-product features
- Build classification and regression models
- Compare model performance using appropriate metrics
- Analyze model robustness and interpretability
- Summarize results and provide final conclusions

---

## Repository Structure

- notebook_1_eda.ipynb  
- notebook_2_preprocessing.ipynb  
- notebook_3_feature_engineering.ipynb  
- notebook_4_classification_models.ipynb  
- notebook_5_regression_models.ipynb  
- notebook_6_model_comparison.ipynb  
- notebook_7_robustness_tests.ipynb  
- notebook_8_interpretability.ipynb  
- notebook_9_interactive_visualization.ipynb  
- notebook_10_final_report.ipynb  
- data/ (dataset files not included)

---

## How to Run the Project

1. Clone the repository.
2. Download the Instacart dataset and place it inside the `data/` folder.
3. Run the notebooks sequentially from notebook_1 to notebook_10.

---

## Models Used

### Classification
- Logistic Regression  
- K-Nearest Neighbors  
- Support Vector Machine  
- Decision Tree  
- Random Forest  
- Gradient Boosting (LightGBM)

### Regression
- Linear Regression  
- Lasso, Ridge, Elastic Net  
- Support Vector Regressor  
- KNN Regressor  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor

---

## Evaluation Metrics

- Classification: Accuracy, Precision, Recall, F1-score, ROC-AUC, PR-AUC
- Regression: MAE, RMSE, R²

---

## Team Contribution

Project tasks were divided among team members. Contributions included
data preprocessing, feature engineering, model development, evaluation,
and report writing. Collaboration was managed using GitHub and Google Colab.

---

## Notes

Some models were trained on sampled data to reduce computational cost
and memory usage while preserving model comparison consistency.

