# Breast Cancer — Binary Classification Task

## Objective
Build and compare multiple binary classification models to predict whether a tumor is:
- **0 = Malignant (Cancerous)**
- **1 = Benign (Non-cancerous)**

Models used :
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## File Structure
Ml-task1-FawazJW32/
│
├── modeling.ipynb      # Model training, evaluation, and comparison
├── README.md           # Project documentation
└── requirements.txt    # Project dependencies
---

## Dataset
Breast Cancer Wisconsin dataset from `scikit-learn`:
- 569 samples
- 30 numerical features
- Binary target
- No missing values

Loaded using:
```python
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()
X = data.data
y = data.target
