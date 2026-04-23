# Loan Approval Prediction

A machine learning project that predicts whether a loan application will be **approved or rejected** based on applicant information.  
This is a **classification problem** in the **Finance domain**, built using Python and Machine Learning.

The project demonstrates data preprocessing, feature encoding, model training, and evaluation using precision and recall.

---

## Objective

To build machine learning models that accurately predict loan approval using historical loan applicant data.

---

## Dataset

- **Source:** Kaggle – Loan Prediction Dataset  
- **File:** `loan_data.csv`  

**Features:**  

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

**Target:** Loan_Status  
- `Y` → Approved  
- `N` → Rejected  

---

## Machine Learning Models

1. **Logistic Regression**  
2. **Random Forest Classifier**  

---

## Evaluation Metrics

- **Precision** – Correctly predicted approvals among predicted approvals  
- **Recall** – Correctly predicted approvals among actual approvals  
- **F1-Score** – Balance of precision and recall  

> Precision and recall are preferred over accuracy due to class imbalance and financial implications.

---

## Project Structure

```bash
Loan_Approval_Prediction/
├── data/
│   └── loan_data.csv
├── notebooks/
│   └── loan_approval_prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/Loan_Approval_Prediction.git
cd Loan_Approval_Prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/loan_approval_prediction.ipynb
```

4. Run all cells to reproduce analysis, model training, and predictions.

---

## Key Learnings

- Handling missing values and categorical variables  
- Feature encoding for machine learning models  
- Comparison of Logistic Regression and Random Forest classifiers  
- Understanding precision, recall, and F1-score in imbalanced datasets  

---

## Future Improvements

- Include additional classifiers (XGBoost, LightGBM)  
- Hyperparameter tuning for better performance  
- Deploy as a web app for interactive loan approval predictions  
- Integrate probability scores to quantify approval confidence  

---

## Author

**Hassan Ali**  
Data Scientist & Machine Learning Engineer  

GitHub: https://github.com/hassan-ali786  

---

⭐ Feel free to fork this repository and explore further improvements!
