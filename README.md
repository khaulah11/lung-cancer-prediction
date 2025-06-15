
# Lung Cancer Prediction using Machine Learning

This project predicts the likelihood of lung cancer based on survey data using 10 machine learning models.

## 📁 Dataset
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer)
- **File**: `survey lung cancer.csv`

## 🧠 ML Models Used
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Naive Bayes (Gaussian & Multinomial)
- Support Vector Classifier (SVC)
- Random Forest
- XGBoost
- Multi-Layer Perceptron
- Gradient Boosting

## 📊 Metrics
- Accuracy
- Precision, Recall, F1-score
- K-Fold & Stratified K-Fold Cross Validation

## 🏆 Best Models
| Model | Accuracy |
|-------|----------|
| Gradient Boosting | ~95.6% |
| Random Forest | ~94.6% |
| MLP / SVC | ~94–95% |

## 🧪 Requirements

To install the required packages:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Place `survey lung cancer.csv` in the project folder.
2. Run the script `lung_cancer_prediction.py`.
3. Check the console for model evaluation results.

## ✍️ Author
This project was created for an assignment on predictive modeling in healthcare.
