# European Bank Customer Retention Analysis (2024)
Power BI • Python • DAX • Customer Analytics

---

## Project Overview

This project analyzes 175,000+ European bank customers to understand why customers churn, which segments are most at risk.  
I built an end-to-end analytics solution using Python and a multi-page Power BI dashboard to deliver actionable insights for business leaders.

---

## Objectives

- Identify the key drivers of customer churn  
- Segment customers into meaningful behavioral groups 
- Deliver a decision-ready Power BI dashboard  

---

## Dataset

**Rows:** 175,028  
**Columns:** 25 variables  

Includes:  
- Demographics: Age, Gender, Country  
- Financials: Balance, Credit Score, Estimated Salary  
- Engagement: Activity status, Number of Products, Tenure  
- Target Variable: `Exited` (1 = churned)
---

## Key Insights

1. Inactive customers are 4× more likely to churn.  
2. Early-tenure customers (1–2 years) churn the most.  
3. High-value customers in Germany show elevated churn risk.  
4. Customers with only 1 product have the highest dropout rate.  
5. Estimated revenue at risk exceeds €40M annually.

---

## Customer Segmentation

A 5-segment model was developed using demographics, behavior, and financial variables:

| Segment | Description |
|--------|-------------|
| High Value | High balance (top 25%), high credit score |
| High Risk | Inactive, 1 product, high churn probability |
| At Risk | Low tenure + below-average credit score |
| Loyal | High tenure, active engagement |
| General | Middle of the distribution |

Segmentation is implemented in both Python and DAX for consistency.

---

## Tech Stack

**Languages:** Python (Pandas, NumPy, Scikit-Learn), SQL, DAX  
**Tools:** Power BI, Jupyter Notebook, Excel  
**Techniques:** Descriptive Analytics, Predictive Modelling, Customer Segmentation, Dashboard Design

---

## Workflow

### 1. Data Cleaning (Python)
- Converted financial fields to numeric  
- Removed formatting noise  
- Handled outliers  
- Created engineered features (ratios, interactions, TF-IDF vectors)  

### 2. Exploratory Analysis
- Churn patterns by demographics  
- Relationship between products, activity, and churn  
- Country-level churn differences  
- Correlation analysis for financial indicators  

### 4. Dashboard Development (Power BI)
Includes two pages:

**Page 1 — Executive Overview**  
KPIs, churn trend, churn by country, product-level churn, churn by segment, high-risk segments.

**Page 2 — Segmentation & Customer Profile**  
KPIs, Segment distribution, average balance, credit score, churn rate by segment.

---

## Business Recommendations

- Re-engage inactive customers with targeted outreach  
- Strengthen onboarding for early-tenure customers  
- Protect high-value customers with premium service offerings  
- Encourage product bundling to reduce single-product churn  
- Implement automated churn monitoring using ML + Power BI  

---


## Live Dashboard
🔗 [View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiZjc2YTBjNzMtZmFkNC00MjQ1LWE3ZDItM2NiMGNmMWRiYjdkIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)



