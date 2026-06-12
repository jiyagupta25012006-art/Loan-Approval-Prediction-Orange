# Loan-Approval-Prediction-Orange
Machine learning-based loan approval prediction system using Orange Data Mining and Logistic Regression with model evaluation and predictive analytics.

# 🤖 Loan Approval Prediction using Orange Data Mining

## 📌 Project Overview

This project demonstrates the use of **Machine Learning** to automate loan approval decisions using **Orange Data Mining** and **Logistic Regression**.

The system analyzes applicant information such as income, credit history, loan amount, education, and employment status to predict whether a loan application is likely to be approved or rejected.

This project showcases how predictive analytics can support financial institutions in making faster and more accurate lending decisions.

---

# 🎯 Objectives

* Automate loan approval prediction
* Reduce manual decision-making effort
* Improve consistency in loan evaluation
* Demonstrate machine learning in finance
* Evaluate model performance using industry metrics

---

# 🏗️ Solution Architecture

```text
Loan Dataset
      ↓
Data Preparation
      ↓
Orange Data Mining
      ↓
Feature Selection
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Loan Approval Prediction
```

---

# ⚙️ Machine Learning Workflow

### Step 1 — Load Dataset

Import the CSV file containing loan applicant information.
<img width="523" height="382" alt="Screenshot 2026-06-12 110356" src="https://github.com/user-attachments/assets/47d9d9da-5e6f-4e30-aa81-ada44fd6ab76" />


### Step 2 — Select Features

Choose important variables:

* Applicant Income
* Loan Amount
* Credit History
* Education
* Property Area
* Employment Status

---

### Step 3 — Train Model

Use Logistic Regression to classify applicants into:

* Approved
* Rejected

---

### Step 4 — Evaluate Model

Performance is measured using:

* Accuracy
* AUC
* Precision
* Recall
* F1 Score

---

# 📊 Dataset Features

| Feature        | Description                 |
| -------------- | --------------------------- |
| Gender         | Applicant Gender            |
| Married        | Marital Status              |
| Education      | Education Level             |
| Income         | Applicant Income            |
| Loan Amount    | Requested Loan              |
| Credit History | Previous Credit Performance |
| Property Area  | Applicant Location          |
| Loan Status    | Target Variable             |

---

# 📸 Project Screenshots

## Orange Workflow

<img width="947" height="505" alt="Screenshot 2026-06-10 140818" src="https://github.com/user-attachments/assets/b033d351-d608-4a4a-9df1-654507e9129f" />

---

## Logistic Regression Evaluation

<img width="959" height="506" alt="Screenshot 2026-06-10 141543" src="https://github.com/user-attachments/assets/08ad9d33-54ee-4246-9852-1d41321f466d" />

---

# 📈 Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 72%   |
| AUC       | 0.845 |
| Precision | 0.714 |
| Recall    | 0.720 |
| F1 Score  | 0.716 |

---

# 🛠️ Tech Stack

| Technology           | Purpose              |
| -------------------- | -------------------- |
| Orange Data Mining   | Workflow Development |
| Logistic Regression  | Classification       |
| CSV Dataset          | Training Data        |
| Predictive Analytics | Decision Making      |

---

# 📂 Repository Structure

```text
Loan-Approval-Prediction-Orange/
│
├── README.md
├── Orange_Loan_Dataset.csv
├── Loan_Approval.ows
│
├── screenshots/
│   ├── loan-approval-workflow.png
│   └── logistic-regression-performance.png
```

---

# 🚀 How to Run

1. Install Orange Data Mining
2. Open Loan_Approval.ows
3. Load dataset
4. Execute workflow
5. Review evaluation metrics

---

# 💼 Skills Demonstrated

* Machine Learning
* Predictive Analytics
* Logistic Regression
* Credit Risk Assessment
* Financial Data Analysis

---

# 👨‍💻 Developed By

## Jiya Gupta

MBA (Applied Finance)

Machine Learning • Financial Analytics • Predictive Modeling
