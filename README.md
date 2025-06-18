# 🏦 Loan Prediction Using Machine Learning

## 📌 Overview
This project aims to predict loan approval status (Yes(1)/No(0)) using machine learning classification algorithms based on applicant information such as income, education, employment, credit history, and more.

---

## 📂 Dataset Description
The dataset contains the following features:

- **Loan_ID**: Unique loan ID  
- **Gender**: Male/Female  
- **Married**: Applicant marital status  
- **Dependents**: Number of dependents  
- **Education**: Graduate/Not Graduate  
- **Self_Employed**: Employment type  
- **ApplicantIncome / CoapplicantIncome**: Monthly income  
- **LoanAmount / Loan_Amount_Term**: Loan details  
- **Credit_History**: Good/bad credit history  
- **Property_Area**: Urban / Semiurban / Rural  
- **Loan_Status (Target)**: Yes (1)(Approved), No (0)(Rejected)

---

## 🧠 ML Approach

### ✅ Steps Followed:
1. Data Preprocessing
2. Handling Missing Values
3. Label Encoding (for categorical data)
4. Feature Scaling (where necessary)
5. Model Building using various ML classifiers:
   - Decision Tree
   - Random Forest
6. Evaluation: Accuracy, Precision, Recall, F1 Score

---

## 📊 Results

| Metric       | Value     |
|--------------|-----------|
| Best Model   | Decison Tree |
| Accuracy     | 93%       |
| Precision    | 91%       |
| Recall       | 76%       |
| F1 Score     | 83%       |

---

## 📈 Visualizations
- Count plots for categorical variables  
- Distribution plots for income and loan amount  
- Correlation heatmap  
- Confusion matrix of best model  

---

## 🚀 Tools and Libraries Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost (optional)

---
