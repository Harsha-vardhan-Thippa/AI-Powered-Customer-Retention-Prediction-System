# Telecom Customer Churn Analysis using Python Matplotlib

> **Exploratory Data Analysis (EDA) project focused on understanding customer churn patterns and retention drivers in the telecom domain.**

---

## Introduction

Customer churn has a direct impact on revenue, profitability, and long-term growth—especially in **subscription-based industries like telecom**.  
This project performs an **in-depth Exploratory Data Analysis (EDA)** to uncover **why customers churn** and identify the **most influential factors affecting retention**.

The analysis emphasizes **data visualization, business interpretation, and actionable insights**, making it both **industry-relevant and interview-ready**.

---

## Project Objectives

- Understand churn behavior across different customer segments  
- Identify high-risk customers based on usage and billing patterns  
- Analyze the impact of tenure, contracts, pricing, and services  
- Translate data insights into **business recommendations**  
- Build a clean and professional **data analytics portfolio project**

---

## Dataset Overview

The dataset contains customer-level information related to demographics, subscribed services, billing, and churn status.

### Key Attributes

| Category | Features |
|-------|---------|
| **Customer Info** | gender, SeniorCitizen, Partner, Dependents |
| **Services** | PhoneService, InternetService, OnlineSecurity, TechSupport |
| **Entertainment** | StreamingTV, StreamingMovies |
| **Billing & Contracts** | Contract, MonthlyCharges, TotalCharges, PaymentMethod |
| **Target Variable** | Churn |

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## Exploratory Data Analysis (EDA)

### 1️⃣ Overall Churn Distribution
- Approximately **25–27% of customers have churned**
- Dataset shows a **moderate churn imbalance**

**Insight:** Customer retention requires immediate attention.

---

### 2️⃣ Demographic Insights

**Gender**
- Churn rates are almost identical across genders  
- Gender is **not a key churn driver**

**Senior Citizens**
- Senior citizens show **significantly higher churn**
- Indicates a need for tailored plans and better support

---

### 3️⃣ Household & Relationship Factors

**Partner Status**
- Customers with partners are **less likely to churn**
- Stability plays a role in retention

**Dependents**
- Customers with dependents have **much lower churn**
- Family responsibility increases service dependency

---

### 4️⃣ Customer Tenure (Critical Insight Area)

**Tenure Distribution**
- Majority of churn occurs within the **first 12 months**
- Long-tenure customers are highly stable

**Tenure vs Churn**
- Churned customers have **short tenure**
- Retained customers show long-term engagement

**Key takeaway:** Early-stage customer experience is crucial.

---

### 5️⃣ Pricing & Revenue Analysis

**Monthly Charges**
- Higher monthly charges correlate with **higher churn**
- Reflects customer price sensitivity

**Total Charges**
- Churned customers have **lower total charges**
- Confirms churn typically happens early
- High-value customers rarely churn

---

### 6️⃣ Contract Type Analysis (Strongest Churn Driver)

- **Month-to-month** contracts show the **highest churn**
- **One-year** contracts significantly reduce churn
- **Two-year** contracts are the most stable

**Conclusion:** Longer commitments improve retention.

---

### 7️⃣ Service Usage Insights

**Internet Service**
- Fiber optic users churn more than DSL users
- Higher cost and expectations may impact satisfaction

**Add-on Services**
- Customers without Online Security or Tech Support churn more
- Add-on services increase trust and service stickiness

---

### 8️⃣ Entertainment Services

- Streaming TV and Movies users tend to stay longer
- Entertainment adds **perceived value and engagement**

---

### 9️⃣ Payment Behavior Analysis

- Electronic check users show the **highest churn**
- Auto-payment users (bank transfer, credit card) are more loyal

**Insight:** Convenience plays a major role in retention.

---

### Correlation Analysis

- Strong positive correlation between **Tenure and TotalCharges**
- MonthlyCharges moderately correlate with TotalCharges
- Confirms tenure as a key revenue contributor

---

## Key Insights Summary

✔ Churn occurs mainly during the early customer lifecycle  
✔ Month-to-month contracts are high-risk  
✔ Pricing strongly influences churn behavior  
✔ Add-on services significantly improve retention  
✔ Senior citizens require focused engagement  
✔ Auto-payment users are more loyal  

---

## Business Recommendations

- Improve onboarding experience during the first **3–6 months**
- Encourage long-term contracts using incentives
- Bundle security and tech support services
- Design customized plans for senior citizens
- Promote auto-payment methods
- Monitor customers with high monthly charges proactively
