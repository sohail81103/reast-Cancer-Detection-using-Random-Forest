# Breast-Cancer-Detection-using-Random-Forest
A machine learning project that predicts whether a tumor is **benign (0)** or **malignant (1)** based on the *Wisconsin Breast Cancer* dataset, using a Random Forest classifier.   Extensive experimentation was performed including **base model**, **manual tuning**, and **hyperparameter search (RandomizedSearchCV &amp; GridSearchCV)**.
## 🚀 Project Workflow

1. **Load & Explore Data**
2. **Encode Target** (M→1, B→0)
3. **Train-Test Split** (80-20)
4. **Feature Scaling** using *StandardScaler*
5. **Train Baseline Random Forest**
6. **Evaluate** (Confusion Matrix, Precision, Recall, F1-score)
7. **Hyperparameter Tuning**
   - Manual loop on `n_estimators`
   - `RandomizedSearchCV`
   - `GridSearchCV`

---

## ✅ Evaluation (Best Model)

| Metric     | Value |
|-----------|------:|
| Accuracy   | 95%   |
| Precision  | 0.92  |
| Recall     | 0.96  |
| F1-Score   | 0.94  |
| Confusion Matrix | `[[63,4],[2,45]]` |

---

## 📂 Directory Structure

├── breast_cancer.csv
├── breast_cancer_random_forest.ipynb
└── README.md


