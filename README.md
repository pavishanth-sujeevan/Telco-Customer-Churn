# CM2604 Machine Learning Coursework – Telco Customer Churn Prediction  
**Robert Gordon University, Aberdeen | Academic Year 2025/2026**  
**Module:** Machine Learning (CM2604)  
**Assessment:** Individual Coursework  
**Student:** Pavishanth Sujeevan  
**Date:** 12 December 2025  

---

### Project Overview
Binary classification task to predict customer churn using the publicly available **"Telco Customer Churn"** dataset (IBM/Watson via Kaggle).

**Models implemented & compared:**
- Decision Tree Classifier (with hyperparameter tuning via GridSearchCV)
- Feed-forward Neural Network (Keras/TensorFlow with hyperparameter tuning via GridSearchCV + SciKeras)

All requirements from the assessment brief are fully satisfied:
- Exploratory Data Analysis with visualisations
- Feature engineering & preprocessing pipeline
- Hyperparameter tuning for both algorithms
- Comprehensive evaluation (Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix, ROC Curve)
- AI ethics & post-deployment discussion included in report

---

### Final Model Performance Comparison

| Model            | Accuracy | Precision | Recall  | F1-Score | ROC AUC |
|------------------|----------|-----------|---------|----------|---------|
| **Decision Tree**    | 0.7608   | 0.5493    | 0.5508  | 0.5501   | **0.7667** |
| **Neural Network**   | **0.7928** | **0.6424** | 0.4947  | **0.5589** | **0.8388** |

**Winner by most important metrics (F1 + ROC AUC):** **Neural Network**

---

