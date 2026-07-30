# Classification Models Comparison

Comparing three machine learning classification models
on student pass/fail prediction using Python and Scikit-learn.

## 📊 Models Compared
- Logistic Regression
- Decision Tree
- Random Forest

## 🏆 Results
All 3 models achieved 100% accuracy on this dataset.

| Model | Accuracy | Overfit Gap |
|-------|----------|-------------|
| Logistic Regression | 100% | 0.0 |
| Decision Tree | 100% | 0.0 |
| Random Forest | 100% | 0.0 |

## 🔍 Key Findings
- Decision Tree used ONLY attendance (importance=1.0)
  to make all decisions — oversimplified
- Random Forest spread importance across all features:
  study_hours=36%, attendance=36%, prev_score=28%
  — more realistic and trustworthy
- Random Forest is more reliable on real messy data
  because 100 trees vote together (ensemble learning)
- Adding trees beyond 100-200 shows diminishing returns

## 🧠 Concepts Covered
- Binary classification
- Logistic Regression and sigmoid function
- Confusion matrix (TP, TN, FP, FN)
- Decision Trees and Gini impurity
- Feature importance
- Random Forest and ensemble learning
- Bagging and feature randomness
- Cross validation
- Overfitting detection

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Lab
