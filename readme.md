# Customer Spending Analysis and Sales Regression

## Project Overview
This project investigates **how customer demographics—age, gender, income, and region—affect spending behavior** in a retail environment.  
It performs **data cleaning, feature engineering, exploratory analysis, and regression modeling** to identify key drivers of customer spending.  
The goal is to provide **actionable insights for retail managers** to optimize marketing, promotions, and sales strategies.

---

## Why It’s Unique
- Combines **demographic analysis** with **predictive modeling**, bridging **business insight** and **technical execution**.
- Handles real-world data issues: missing values, categorical encoding, and feature engineering.
- Predicts **monthly spend** for customers, helping guide **marketing campaigns and sales planning**.

---

## Dataset
- Provided in `data/customers.json`
- Sample features: `customer_id`, `age`, `gender`, `region`, `income`, `monthly_spend`

---

## Tools & Techniques
- **Python & Pandas** – data extraction & preprocessing
- **NumPy** – numerical operations
- **Seaborn & Matplotlib** – exploratory data analysis & visualization
- **Statsmodels** – multiple linear regression modeling & interpretation
- **Feature Engineering** – yearly spend, encoded categorical variables
- **GitHub & Colab** – hosting and sharing interactive notebooks

---

## Analysis Steps
1. Load and clean JSON data  
2. Handle missing values and encode categorical variables  
3. Create new features (e.g., yearly spend)  
4. Perform EDA: histograms, boxplots, correlation heatmaps, scatterplots  
5. Build a multiple linear regression model to predict monthly spend  
6. Interpret coefficients to identify key drivers of spending  

---

## Business Impact
- Identify **high-value customer segments**
- Recommend **targeted promotions and marketing campaigns**
- Predict **customer spending** for sales planning

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/<LaksitaSenthilkumar>/customer-spending-analysis.git
