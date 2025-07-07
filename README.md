# loan-eligibility-ml

A machine learning project to predict loan approval status using logistic regression, trained on Kaggle's Loan Prediction dataset.

---

## 📁 Dataset

- **Source**: [Kaggle – Loan Prediction Problem Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- **File used**: `train.csv` (for training and evaluation)

---

## 🎯 Objective

Build a classification model to predict whether a loan application will be approved (Y) or rejected (N) based on applicant details such as gender, income, education, credit history, etc.

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 🧹 Preprocessing Steps

- Handled missing values using mode and median
- Converted categorical variables to numerical using one-hot encoding (`get_dummies`)
- Split dataset into training and testing sets
- Scaled features using `StandardScaler` for better model convergence

---

## 🤖 Model Used

- Algorithm: Logistic Regression (from `sklearn`)
- Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

---

## 📊 Results

- **Accuracy**: ~79%
- **Confusion Matrix**:
[[16 27]
[ 1 79]]
- **Observation**:
- The model performs well in predicting approved loans
- It shows some false positives (predicting approval when it should reject)

---

## 🚀 Next Steps

- Try other ML models: Random Forest, XGBoost
- Perform cross-validation to improve generalization
- Deploy using Streamlit or Flask for interactive prediction

---

## 📁 Files in This Repository

| File                         | Description                        |
|------------------------------|------------------------------------|
| `README.md`                  | Project overview and results       |
| `loan_prediction_model.ipynb`| Jupyter notebook with full code    |
      

