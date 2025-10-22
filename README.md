# Customer Churn Analysis – Dollar Bank

## Executive Summary

This project presents an end-to-end customer churn analysis for Dollar Bank’s credit card division using SQL, Python, and Tableau. The goal was to identify key drivers of churn, highlight high-risk customer segments, and provide data-driven recommendations to improve retention.
With churn rates climbing, the bank sought actionable insights to guide proactive retention strategies. The project delivered a comprehensive analysis pipeline, from raw data extraction to interactive visualization, to inform business decisions.

---

## Business Problem
The bank faced a 16% customer churn rate, with noticeable declines in transaction frequency and spending among departing clients.
Understanding why customers leave, which segments are most at risk, and what retention actions can be taken became crucial for improving customer lifetime value and profitability.


---

## Methodology

### 1. SQL Analysis
- Merged and queried three datasets.

- Answered business questions on demographics, income categories, and churn patterns.

- Segmented customers by age group, marital status, and card type.

### 2. Python EDA
- Cleaned data by handling missing values and correcting inconsistencies.

- Analyzed distributions, detected outliers, and assessed correlations.

- Identified significant predictors of churn using statistical and visual techniques.

### 3. Tableau Dashboard
- Visualized KPIs, demographics, and spending behaviors.

= Enabled interactive filtering to explore high-risk customer segments.

**Link**:   
- [Tableau Dashboard](https://public.tableau.com/app/profile/ayan.abbas/viz/BankCustomerChurnDashboard_17544842879370/Dashboard1)  

---

## Skills  

- **SQL:** Data extraction, transformation, and segmentation queries  
- **Python:** Data cleaning, exploratory data analysis (EDA), and churn pattern detection  
- **Tableau:** KPI visualization, demographic segmentation, and interactive dashboard design  


---

## Results & Business Recommendation  

### Key Insights  

#### Overall Churn  
- **Churn rate:** 16% (1 in 6 customers)  
- **Average transaction amount:** $3,095 (churned) vs. $4,404 (retained)  
- Lower spending and fewer transactions are strongly linked to churn  

#### Demographics  
- **Average customer age:** 46 years; more females than males  
- **Highest churn:** Females aged 41–50 (4.4% churn rate)  
- **Tenure impact:** Customers with 25–36 months tenure showed highest churn (5% females, 3.6% males)  
- **Largest at-risk group:** Female blue cardholders earning less than $40K (559 customers)  

#### Behavior Patterns  
- Customers with **<100 transactions** and **spending < $5K** are most likely to churn  
- **Pareto effect:** 20% of customers account for ~80% of total churn  
- **At-risk profiles:** Female graduates (married or single) and male graduates (single)  

---
### Business Recommendations  

#### Retention Focus  
- Prioritize long tenure and established customers  

#### Targeted Campaigns  
- Launch financial literacy programs for graduates  
- Build lifestyle partnerships offering exclusive discounts and rewards  

#### Product Incentives  
- Introduce cashback rewards, waived annual fees, and sign-up bonuses  

#### Credit Counseling  
- Provide low-income customers with guidance and resources to improve credit health  

**Expected Outcome:**  
- Reduce churn from **16% → <7%**, aligning with industry benchmarks  

---

### Next Steps  
- Automate churn data refresh using **SQL → Python → Tableau** pipelines for near real-time updates  
- Implement **predictive churn modeling** to enable proactive customer retention actions  
- Continuously track **churn reduction KPIs** and evaluate the effectiveness of retention strategies on a quarterly basis  


