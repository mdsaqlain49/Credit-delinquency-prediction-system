# Credit-delinquency-prediction-system
Credit delinquency prediction project using EDA, XGBoost, risk profiling, and AI-driven business recommendations, completed as part of the TATA Group GenAI Data Analytics Job Simulation.
# Credit Delinquency Prediction System

🏅 Completed as part of the **TATA Group – GenAI Powered Data Analytics Job Simulation (Forage)**

## Project Overview
This project focuses on analyzing customer credit behavior and predicting delinquency risk using machine learning techniques. The goal is to identify high-risk customers early and recommend proactive interventions to reduce financial losses.

The project includes:
- Exploratory Data Analysis (EDA)
- Risk profiling and segmentation
- Predictive modeling using XGBoost
- Strategic recommendations for collections
- Responsible AI and fairness considerations

---

## Business Problem
Financial institutions face losses due to customer delinquency and late repayments. This project aims to predict high-risk customers and enable proactive intervention before severe financial distress occurs.

---

## Objectives
✔ Analyze customer behavior and delinquency patterns  
✔ Identify high-risk customer segments  
✔ Build a predictive model for delinquency forecasting  
✔ Recommend business strategies to reduce delinquency  
✔ Ensure fairness and explainability in AI predictions  

---

## Dataset Features
The dataset includes:

- Customer Age
- Income
- Employment Status
- Credit Score
- Credit Utilization
- Loan Balance
- Payment History
- Debt-to-Income Ratio
- Location
- Card Type
- Delinquency Status

---

## Exploratory Data Analysis (EDA)

### Key Findings:
- Missing values found in Income, Loan_Balance, and Credit_Score
- Inconsistent Employment_Status labels required standardization
- Credit utilization above 100% indicated extreme-risk customers
- Strong categorical risk drivers:
  - Age group (46–60)
  - Location
  - Employment status
  - Card type

### High-Risk Segments:
- Age 46–60 → Highest delinquency rate
- Credit utilization >30% → Significant risk increase
- Los Angeles customers → Higher delinquency rate

---

## Data Preprocessing

Techniques used:

- Median imputation for missing values
- Standardization of categorical labels
- Feature engineering
- One-hot encoding
- Behavioral scoring for payment history

---

## Machine Learning Model

### Algorithm:
**XGBoost Classifier**

Why XGBoost?
- Handles tabular financial data effectively
- Captures non-linear relationships
- High predictive performance
- Better recall for delinquency detection

---

## Model Evaluation Metrics

The model was evaluated using:

- AUC-ROC
- Recall
- F1-Score
- Fairness testing

Priority:
Maximize **Recall** to reduce False Negatives (missing risky customers).

---

## Strategic Recommendations

### Financial Health Nudge System

Recommended intervention:

- Trigger alerts when credit utilization exceeds 30%
- Provide budget guidance
- Offer payment restructuring options
- Enable proactive customer support

Goal:

Reduce delinquency among high-risk customers within 6 months.

---

## Responsible AI Considerations

Implemented safeguards:

- SHAP explainability
- Bias testing
- Demographic parity checks
- Equal opportunity constraints

---

## Project Structure

```bash
credit-delinquency-prediction-system/
│
├── dataset/
├── reports/
├── presentation/
├── certificates/
├── images/
└── README.md
```

---

## Files Included

- Dataset (.xlsx)
- EDA Report
- Predictive Modeling Report
- Strategic Recommendation Report
- Presentation Slides
- TATA Forage Completion Certificate

---

## Certification

Completed practical tasks in:

✔ Exploratory data analysis and risk profiling  
✔ Predicting delinquency with AI  
✔ Business reporting and storytelling  
✔ Implementing AI-driven collections strategies  

Certificate:

**TATA Group – GenAI Powered Data Analytics Job Simulation (Forage)**

---

## Tools & Technologies

Python • Pandas • NumPy • XGBoost • Scikit-learn • Matplotlib • Excel

---

## Outcomes

This project demonstrates:

- Data Cleaning
- EDA
- Machine Learning
- Business Analytics
- Risk Analysis
- AI Explainability
- Data Storytelling

---

## Author

**Mohammed Saqlain**
