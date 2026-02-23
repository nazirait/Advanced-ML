# Advanced Machine Learning 

This project investigates the impact of different feature selection techniques and classification algorithms on both artificial and real-world datasets.

### Feature Selection Methods Evaluated:
- Boruta
- RFE + SVM
- Lasso
- Chi-Square
- Correlation Analysis

* Each selector’s key parameter was tuned based on the performance of an XGBoost classifier trained on selected features.

### Classifiers Evaluated:
- Random Forest
- Logistic Regression
- Decision Tree
- Gradient Boosting
- AdaBoost
- Gaussian Naive Bayes
- LDA
- QDA
- SVM
- XGBoost

### Datasets:
1. Artificial Dataset

| Component         | Best Choice                    |                                                                |
| ----------------- | ------------------------------ | --------------------------------------------------------------------- |
| Feature Selector  | **Chi-Square**                 | 10 features were selected (best accuracy / smallest feature set trade-off) |
| Classifier        | **Random Forest**              | Highest prediction accuracy                                           |
| Final Combination | **Chi-Square + Random Forest** | Best overall performance                                              |

### Final performance: Chi-Square + Random Forest has achieved best overall performance 
<img width="970" height="344" alt="image" src="https://github.com/user-attachments/assets/c54d756d-fab7-4bb0-bc6b-86cd8df8d1ab" />

2. SMS Spam Classification Dataset

| Model               | Accuracy   | Score(BA, m) |
| ------------------- | ---------- | ------------ |
| **Random Forest**   | **97.67%** | **0.9266**   |
| XGBoost             | 97.52%     | 0.9212       |
| Decision Tree       | 97.45%     | 0.9177       |
| SVM                 | 96.97%     | 0.9118       |
| Gradient Boosting   | 96.98%     | 0.9051       |
| AdaBoost            | 95.76%     | 0.8788       |
| Logistic Regression | 95.26%     | 0.8527       |
| LDA                 | 95.08%     | 0.8409       |
| GaussianNB          | 92.91%     | 0.8391       |
| QDA                 | 91.19%     | 0.8343       |

### Final performance: Lasso + Random Forest has achieved best overall performance 

-----------------------------------------------------------------------------------------------------

Got it! Here's a **compact, recruiter-friendly version** suitable for a GitHub README:

---

#### Technologies & Concepts Used

**Programming:** Python
**Data Processing & Feature Engineering:** NumPy, pandas, CountVectorizer
**Feature Selection:** Boruta, RFE (SVM), Lasso (L1), Chi-Square, Correlation Analysis
**Machine Learning Models:** Random Forest, Logistic Regression, Decision Tree, Gradient Boosting, AdaBoost, Gaussian Naive Bayes, LDA/QDA, SVM, XGBoost
**Model Evaluation & Optimization:** Accuracy Score, Train/Test Split, Hyperparameter Tuning



