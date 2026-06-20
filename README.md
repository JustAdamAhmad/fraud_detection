# Insurance Fraud Detection — Predictive Risk Modelling

A machine learning case study for an insurance company looking to reduce fraud losses while protecting genuine customers from unnecessary referrals.

---

## Overview

This repository contains a technical report and predictive model built around a real-world insurance fraud dataset. The goal is to flag potentially fraudulent claims for further investigation — without incorrectly referring genuine customers.

The core challenge is a two-sided business problem:

- **Referring a genuine claim** causes customer stress and leads to churn — a direct revenue loss for the company
- **Missing a fraudulent claim** also costs the company money

The model needs to balance both risks fairly, using an **unbiased predictive approach** that minimises harm on either side.

---

## Objective

> Build a predictive model capable of flagging and referring potential fraud cases for further investigation, while keeping false referrals of genuine customers as low as possible.

---

## Repository Structure

```
├── data/                  # Dataset (raw and processed)
├── notebooks/             # Exploratory data analysis and modelling
├── src/                   # Source code for preprocessing and model pipeline
├── report/                # Full technical report
└── README.md
```

---

## 🔧 Tools & Technologies

- **Python** — core language
- **Pandas / NumPy** — data manipulation
- **Scikit-learn** — model training and evaluation
- **Matplotlib / Seaborn** — visualisation
- **Jupyter Notebook** — analysis and reporting

---

## Approach

1. **Exploratory Data Analysis** — understanding class imbalance, feature distributions, and fraud patterns
2. **Preprocessing** — handling missing values, encoding, and feature engineering
3. **Modelling** — training and comparing classification models
4. **Bias & Fairness Check** — ensuring the model does not disproportionately flag any customer group
5. **Evaluation** — assessed using precision, recall, F1-score, and AUC-ROC with a focus on minimising false referrals


---

## Business Constraint

> Any genuine claim that is incorrectly referred is assumed to result in losing that customer.

This constraint directly shapes how the model is evaluated — minimising **false positives** is as important as catching fraud.

---

##
Status

🔄 In progress — part of MSc Artificial Intelligence coursework at the University of Leeds.
