# Telecom Customer Churn Analysis using Python Matplotlib
---

## 1️⃣ Introduction

Customer churn is a critical challenge for telecom and subscription-based businesses, as retaining existing customers is more cost-effective than acquiring new ones. Understanding the reasons behind customer churn helps organizations improve customer satisfaction and design effective retention strategies.

This project focuses on **Exploratory Data Analysis (EDA)** to analyze customer churn behavior using historical telecom customer data. The objective is to identify **patterns, trends, and key factors influencing churn** through data visualization and statistical analysis.

---

## 2️⃣ Problem Statement

The telecom company is facing customer attrition.  
The goal of this project is to:

- Analyze customer data to understand churn behavior  
- Identify factors contributing to customer churn  
- Provide actionable insights to improve customer retention  

This project does **not include machine learning or prediction models**.  
It strictly focuses on **data understanding and insight generation**.

---

## 3️⃣ Dataset Description

The dataset contains customer demographic details, service subscriptions, billing information, and churn status.

### Dataset Attributes

| Category | Columns |
|--------|--------|
| Customer Details | gender, SeniorCitizen, Partner, Dependents |
| Services | PhoneService, InternetService, OnlineSecurity, TechSupport |
| Entertainment | StreamingTV, StreamingMovies |
| Billing & Contracts | Contract, MonthlyCharges, TotalCharges, PaymentMethod |
| Target Variable | Churn |

---

## 4️⃣ Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 5️⃣ Data Understanding & Preparation

- The dataset structure and data types were examined  
- Numerical and categorical columns were identified  
- `TotalCharges` column was converted to numeric format  
- No advanced data cleaning was performed, as the focus was on EDA  

---

## 6️⃣ Exploratory Data Analysis (EDA)

### 6.1 Churn Distribution Analysis

- Around **26–27% of customers have churned**
- The dataset is moderately imbalanced

**Observation:**  
A significant number of customers are leaving, indicating a retention concern.

---

### 6.2 Demographic Analysis

#### Gender vs Churn
- Male and female customers show nearly identical churn rates  
- Gender is not a significant churn driver  

#### Senior Citizen vs Churn
- Senior citizens exhibit higher churn  
- Indicates a need for targeted engagement strategies  

---

### 6.3 Relationship & Household Analysis

#### Partner vs Churn
- Customers with partners churn less  
- Relationship stability improves retention  

#### Dependents vs Churn
- Customers with dependents show very low churn  
- Family responsibility increases service dependency  

---

### 6.4 Tenure Analysis

#### Tenure Distribution
- High churn occurs during the first 12 months  
- Long-tenure customers are more stable  

#### Tenure vs Churn
- Churned customers have low median tenure  
- Retained customers show long-term engagement  

**Key Insight:**  
Early customer experience is critical.

---

### 6.5 Charges Analysis

#### Monthly Charges vs Churn
- Churned customers generally pay higher monthly charges  
- Indicates price sensitivity  

#### Total Charges vs Churn
- Churned customers have lower total charges  
- Confirms churn happens early in the customer lifecycle  
- High-value customers rarely churn  

---

### 6.6 Contract Analysis

#### Contract Type Distribution
- Majority of customers are on month-to-month contracts  

#### Contract vs Churn
- Month-to-month contracts show the highest churn  
- One-year contracts reduce churn significantly  
- Two-year contracts have the lowest churn  

**Conclusion:**  
Longer contracts increase customer retention.

---

### 6.7 Service Usage Analysis

#### Internet Service vs Churn
- Fiber optic users churn more than DSL users  
- Higher costs and expectations may influence dissatisfaction  

#### Online Security & Tech Support
- Customers without add-on services churn more  
- Add-on services improve customer trust and retention  

---

### 6.8 Streaming Services Analysis

- Streaming TV and Movies users tend to stay longer  
- Entertainment services add perceived value  

---

### 6.9 Payment Method Analysis

- Electronic check users show the highest churn  
- Auto-payment users are more loyal  

**Insight:**  
Convenient payment methods reduce churn.

---

### 6.10 Correlation Analysis

- Strong positive correlation between Tenure and TotalCharges  
- Moderate correlation between MonthlyCharges and TotalCharges  
- Confirms tenure as a key revenue driver  

---

## 7️⃣ Key Insights Summary

- Churn mainly occurs early in the customer lifecycle  
- Month-to-month contracts pose high churn risk  
- Higher monthly charges increase churn  
- Add-on services significantly reduce churn  
- Senior citizens require focused retention strategies  
- Auto-payment users are more loyal  

---

## 8️⃣ Business Recommendations

- Improve onboarding experience in the first 3–6 months  
- Encourage long-term contracts using incentives  
- Bundle Online Security and Tech Support services  
- Provide customized plans for senior citizens  
- Promote auto-payment options  
- Monitor high monthly charge customers proactively  

---

## 9️⃣ Conclusion

This project demonstrates how exploratory data analysis can uncover important customer churn drivers. The analysis shows that tenure, contract type, pricing, and service add-ons play a significant role in customer retention. These insights can help businesses design effective strategies to reduce churn.

---

## Future Scope

- Build a churn prediction model using machine learning  
- Perform feature importance analysis  
- Develop dashboards using Power BI or Tableau  
- Segment customers based on churn risk  
