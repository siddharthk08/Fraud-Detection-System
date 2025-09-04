
# Fraud Detection System 

An end-to-end **Machine Learning pipeline** to detect fraudulent financial transactions.  
The system is designed to handle large-scale datasets efficiently and identify suspicious activities with high precision.

---

## 📌 Key Features
- **Robust Data Handling**: Chunked CSV reading for huge datasets with memory optimization.
- **Data Cleaning**: Handles missing values, outliers, and multicollinearity.
- **Time-Aware Splitting**: Preserves transaction order when timestamps are available, otherwise uses stratified split.
- **Class Imbalance Handling**: Class weights to ensure fairness between fraud and non-fraud classes.
- **Model Training**:
  - Logistic Regression (baseline).
  - HistGradientBoostingClassifier (tree-based, scalable).
- **Evaluation Metrics**: ROC-AUC, PR-AUC, F1-score, confusion matrix.
- **Model Interpretability**: Permutation importance & global feature effect plots.
- **Deployment Ready**: Trained models saved as `.joblib` artifacts.

---
