#  Telecom Customer Churn Analysis

An end-to-end Data Analysis & Machine Learning project to understand **customer churn in a telecom company**.  
The project includes **data cleaning, exploratory data analysis (EDA), machine learning models, feature importance analysis, and dashboarding with Power BI**.

---

##  Project Workflow

1. **Data Loading** – Used the Telco Customer Churn dataset (Kaggle).  
2. **Data Cleaning & Preprocessing** – Handled missing values, categorical encoding, and feature scaling.  
3. **Exploratory Data Analysis (EDA)** – Analyzed churn patterns across demographics, services, and account info.  
4. **Machine Learning Models**  
   - Logistic Regression  
   - Random Forest Classifier  
   → Compared accuracy, precision, recall, and ROC-AUC.  
5. **Feature Importance** – Identified key factors influencing churn (e.g., tenure, contract type, payment method).  
6. **Export for Power BI** – Final processed CSV generated for dashboard visualization.
7. **Link** - Churn Analysis_googlecollab

---

##  Power BI Dashboard

The exported data was used to build an **interactive Power BI Dashboard** with:  
- Churn rate % indicator  
- Churn by gender & senior citizen status  
- Churn by contract type (Month-to-Month, One year, Two-year)  
- Churn by payment method & internet service  
- Tenure vs Churn trend line  
- Slicers for filtering (gender, internet type, payment method, contract type, senior citizen, etc.)
- **LINK**-https://app.powerbi.com/view?r=eyJrIjoiMzk1NTQ4NDgtMzhmMy00MGFhLTk4OWEtYjNkMmUyZWUxNGU5IiwidCI6ImE2ZGJkZGRlLTU3OTgtNGViYS1hNWE4LTc4ODA3ZTgyZDllYiJ9

##  Dataset
- **Source:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Rows:** ~7,000 customers  
- **Target Variable:** `Churn (Yes/No)

##  Key Insights
- Month-to-month contracts show the **highest churn rate**.  
- Customers paying via **electronic check** are more likely to churn.  
- **Tenure** is strongly negatively correlated with churn → the longer customers stay, the less likely they are to churn.  
- **Fiber optic internet service** users churn more compared to DSL.  
