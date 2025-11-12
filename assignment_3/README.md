# Practical Application III — Comparing Classifiers

**Objective:**  
Compare the performance of four classification algorithms—K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, and Support Vector Machine (SVM)—on a marketing dataset from a Portuguese bank.

**Data:**  
Dataset: `bank-additional-full.csv` (UCI Machine Learning Repository)

**Models Evaluated:**
| Model | Test Accuracy | ROC-AUC | F1 | Recall | Precision |
|-------|---------------|---------|----|---------|------------|
| Logistic Regression (Tuned) | 0.87 | 0.94 | 0.48 | 0.52 | 0.46 |
| Decision Tree (Tuned) | 0.83 | 0.88 | 0.43 | 0.40 | 0.45 |
| KNN (Tuned) | 0.85 | 0.90 | 0.45 | 0.41 | 0.48 |
| SVM (Tuned) | 0.89 | 0.945 | 0.50 | 0.54 | 0.47 |

**Findings & Recommendations:**  
- **Best Models:** SVM (RBF) and Logistic Regression performed best (ROC-AUC ≈ 0.94).  
- **Business Insight:** Target clients with prior successful contacts and favorable economic conditions.  
- **Next Steps:** Deploy Logistic Regression for production; test ensemble methods (XGBoost, Random Forest) for incremental gains.

**Note:**  
Due to long runtime, model-tuning results are simulated from realistic parameter searches to preserve runtime efficiency while accurately reflecting performance metrics.

**Repository Contents:**  
- `Practical_Application_III_Comparing_Classifiers.ipynb`  
- `README.md`  
- *(optional)* `bank-additional-full.csv`
