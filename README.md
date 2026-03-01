# Cloover Credit Risk Analysis

Data science case study analyzing 1,000 solar loan customers to predict defaults and optimize loan pricing.

---

## What This Project Does

- Segments customers into **Low, Medium, High risk** tiers using credit score, income, loan amount, and payment behavior
- Trains two ML models (Logistic Regression, Random Forest) to predict **Probability of Default (PD)**
- Identifies a **pricing gap**: high-risk customers default at 6x the rate of low-risk but are charged almost the same interest rate

---

## Project Structure

```
├── notebooks/
│   ├── Cloover_Case_Study.ipynb
│   
├── data/
│   └── Case_Study_Data_Science_Intern.xlsx
└── outputs/
    └── cloover_credit_model.pkl
```

---

## Key Results

| Model | Accuracy | AUC |
|---|---|---|
| Logistic Regression | 94.0% | 0.998 |
| Random Forest | 100.0% | 1.000 |

---

## Setup

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl mlflow
jupyter notebook
```

---

## Data

Three sheets from the case study Excel file: Loan Data (1,000 customers), Payment History (12,000 records), SCHUFA PD Distribution benchmark.