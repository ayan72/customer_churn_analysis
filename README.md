# 📊 Customer Churn Analysis – Dollar Bank

## 📝 Introduction
This is an **end-to-end customer churn analysis** project for **Dollar Bank**, combining:
- **SQL** – Data extraction and transformation
- **Python** – Deep-dive exploratory data analysis (EDA)
- **Tableau** – Interactive dashboard creation

The objective was to **identify the main drivers of churn** in the bank’s credit card services, locate **high-risk customer segments**, and **recommend targeted strategies** to improve retention.

With churn rates increasing, the bank required actionable insights to guide proactive customer retention programs. This project diagnoses the churn problem and offers **data-backed recommendations**.

---

## 🔍 Methodology
### **1. SQL Analysis**
- Merged and queried three datasets.
- Answered business questions on demographics, income categories, and churn patterns.
- Segmented customers by age group, marital status, and card type.

### **2. Python EDA**
- Data cleaning: handled missing values, corrected inconsistencies.
- Analyzed distributions, detected outliers, assessed correlations.
- Identified significant predictors of churn.

### **3. Tableau Dashboard**
- Visualized KPIs, demographics, and spending behaviors.
- Enabled interactive filtering to drill into high-risk segments.

📄 **Link**:   
- [Tableau Dashboard](https://public.tableau.com/app/profile/ayan.abbas/viz/BankCustomerChurnDashboard_17544842879370/Dashboard1)  

---

## 📈 Key Insights

### **Overall Churn**
- **Churn rate**: 16% (~1 in 6 customers).  
- Churned customers’ **average transaction amount**: **$3,095** vs. **$4,404** for retained customers.  
- Lower transaction frequency and spending strongly linked to churn.

### **Demographics**
- **Average age**: 46 years; more female than male customers.
- **Highest churn**: Females aged 41–50 (4.4% churn rate).
- **Tenure effect**: Established customers (25–36 months) had highest churn (5% females, 3.6% males).
- Largest churn segment: **Female blue cardholders earning < $40K** (559 customers).

### **Behavior Patterns**
- Customers with **<100 transactions** and **spending < $5K** are most likely to churn.
- **Pareto Analysis**: 20% of customers account for ~80% of churn.
- Key at-risk groups:
  - Female graduates (married or single)
  - Male graduates (single)

---

## 💡 Recommendations
- **Retention Focus**:
  - Prioritize established and long-term customers.
  - Pay special attention to female blue cardholders earning < $40K.
- **Targeted Campaigns**:
  - Financial literacy webinars and resources for graduates.
  - Partnerships with lifestyle brands to provide member discounts.
  - Loyalty programs with waived fees, financial planning, or investment advice.
- **Product Incentives**:
  - Cashback rewards, sign-up bonuses, reduced interest rates.
- **Credit Counseling**:
  - Support for low-income cardholders to improve credit scores.

📉 **Expected Impact**: Reduce churn from 16% to below 7% — an industry-acceptable benchmark.
