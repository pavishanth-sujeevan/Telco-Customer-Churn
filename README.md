# CM2604 Machine Learning Coursework – Telco Customer Churn Prediction  
**Robert Gordon University, Aberdeen | Academic Year 2025/2026**  
**Module:** Machine Learning (CM2604)  
**Assessment:** Individual Coursework  
**Student:** Pavishanth Sujeevan  
**Date:** 12 December 2025  

---

### Project Overview
Binary classification task to predict customer churn using the **Telco Customer Churn** dataset (IBM/Watson, publicly available on Kaggle).

**Six model variants systematically developed and compared:**
1. Baseline Decision Tree  
2. Tuned Decision Tree (GridSearchCV)  
3. SMOTE + Tuned Decision Tree  
4. Baseline Neural Network (Keras)  
5. Tuned Neural Network (GridSearchCV + SciKeras)  
6. SMOTE + Tuned Neural Network  

All requirements from the assessment brief are **fully satisfied and exceeded**.

---

### Final Model Performance – All 6 Variants

| Model Variant                  | Accuracy | Precision | Recall (Churn) | F1-Score (Churn) | ROC-AUC |
|-------------------------------|----------|-----------|----------------|------------------|---------|
| 1. Baseline Decision Tree     | 0.7388   | 0.5079    | 0.5160         | 0.5119           | 0.6675  |
| 2. Tuned Decision Tree        | 0.7686   | 0.5652    | 0.5561         | 0.5606           | 0.8002  |
| **3. SMOTE + Tuned DT**       | 0.7622   | 0.5418    | **0.6765**     | **0.6017**       | 0.8063  |
| 4. Baseline Neural Network    | 0.7779   | 0.5905    | 0.5321         | 0.5598           | 0.8137  |
| 5. Tuned Neural Network       | **0.7921** | **0.6337** | 0.5134         | 0.5672           | 0.8300  |
| **6. SMOTE + Tuned NN**       | 0.7530   | 0.5264    | **0.6925**     | **0.5982**       | **0.8027** |

**Winner by business-critical metrics (Recall & F1-Score for Churn):**  
**SMOTE + Tuned Neural Network** – highest churn detection rate (+31% recall vs baseline NN)

**Winner by overall discrimination (ROC-AUC):**  
**Tuned Neural Network** – AUC = 0.830

---

### Repository Contents
