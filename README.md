# Loan Approval Prediction

## 📌 Project Overview
This project predicts whether a loan application will be **approved or rejected** based on applicant information.  
It is a **classification problem** in the **Finance domain**, built using Python and Machine Learning.

The goal is to practice:
- Data preprocessing
- Handling missing values
- Feature encoding
- Model training
- Model evaluation using precision & recall

---

## 🎯 Objective
To build machine learning models that can accurately predict loan approval using historical loan applicant data.

---

## 📊 Dataset
- Source: Kaggle (Loan Prediction Dataset)
- File used: `loan_data.csv`

### Features:
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  

### Target:
- **Loan_Status**
  - `Y` → Approved  
  - `N` → Rejected  

---

## 🧠 Machine Learning Models
The following models are used:

1. **Logistic Regression**
2. **Random Forest Classifier**

---

## 📈 Evaluation Metrics
Models are evaluated using:
- Precision  
- Recall  
- F1-Score  

These metrics are more reliable than accuracy for loan approval problems.

---

## 🗂️ Project Structure
Loan_Approval_Prediction/
├── data/
│ └── loan_data.csv
├── notebooks/
│ └── loan_approval_prediction.ipynb
├── models/
│ ├── logistic_model.pkl
│ └── random_forest_model.pkl
├── requirements.txt
└── README.md


---

## ⚙️ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt

jupyter notebook
notebooks/loan_approval_prediction.ipynb

