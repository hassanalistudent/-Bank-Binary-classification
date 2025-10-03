# Bank Binary Classification – Kaggle Playground Series (S5E8)

This project is a solution for the [Kaggle Playground Series – Season 5, Episode 8](https://www.kaggle.com/c/playground-series-s5e8/overview) competition. The objective was to build a binary classification model to predict whether a client would subscribe to a bank term deposit based on structured marketing and personal data.

## 🧠 Model Overview
- **Task**: Binary classification (0 = No, 1 = Yes)
- **Dataset Size**: 150,000 rows
- **Evaluation Metric**: ROC AUC

## 📊 Results
- **Accuracy**: 0.80175  
- **ROC AUC**: 0.85312  

### Classification Report:
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0.0   | 0.96      | 0.81   | 0.88     | 131,902 |
| 1.0   | 0.35      | 0.72   | 0.47     | 18,098  |

- **Macro Avg F1**: 0.67  
- **Weighted Avg F1**: 0.83  

## ⚙️ Tools & Techniques
- Python (scikit-learn, pandas, matplotlib)
- Feature engineering and model tuning
- Evaluation using classification metrics and ROC curve

## 📁 Files Included
- `Bank Binary Classification.ipynb`: Full notebook with preprocessing, modeling, and evaluation
- `Data files.zip`: Training and test datasets

## 🔗 Competition Link
Visit the official Kaggle competition page: [Binary Classification with a Bank Dataset – S5E8](https://www.kaggle.com/c/playground-series-s5e8/overview)

---

Feel free to fork, explore, or contribute. This project reflects my growing expertise in machine learning and model evaluation.
