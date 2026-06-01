# Loan Approval Prediction

A machine learning project that predicts whether a loan application will be **approved or rejected** based on applicant information.  
This is a **classification problem** in the **Finance domain**, built using Python and Machine Learning.

The project demonstrates data preprocessing, feature encoding, model training, and evaluation using precision and recall.

---

## Video Demo

<video src="https://github.com/user-attachments/assets/a6776eec-a6a7-4a88-93df-be082bbebb5e" width="100%" controls></video>

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
loan_approval_prediction/
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
git clone https://github.com/hassan-ali786/loan_approval_prediction.git
cd loan_approval_prediction
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
Data Scientist & ML Engineer  

--

⭐ Feel free to fork this repository and explore further improvements!
