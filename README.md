# Telco_Customer_Churn_Analysis
This project analyzes customer churn behavior using the IBM Telco dataset. The goal is to identify patterns behind customer high customer churn rates and build an interactive dashboard to support business decision-making.  The workflow combines data preparation in Alteryx and visualization in Tableau.
# Dataset
- Source: Kaggle – IBM Telco Customer Churn Dataset
- Records: ~7,000 customers

# Key Insights
- Customers on month-to-month contracts are more than 3 times more likely to churn
- Half of month-to-month customers with low tenure (< 12 months) are more likely to churn within that first year
- Encourage new customers to sign 1 or 2 year contracts, by adding incentives to sign a longer contract, such as an annual pricing deal

- Customers who pay by electronic check have the highest churn rate of 45%.
- Customers who pay by Credit Card have the lowest churn rate at 15%.
- Incentivize a transition to an automatic payment (auto-pay) method i.e. offer a one-time or monthly discount
  
# If I had more time
- I would build a predictive churn model in Alteryx to identify customers most likely to churn. 
- Incorporate monthly churn trends to identify seasonality

# Data Preparation
- Rename variables using snake case to improve interpretability for analysis and visualizations
- Change data types for tenure, contract, monthly charges, total charges, and churn 
- Created calculated fields Churn_Flag, Tenure_Group, Monthly_Charge_Group, Contract_Risk
- Used grouping and summarization to calculate churn rate, customer counts, churn by contract type, churn by payment method
# Analytical Techniques
- Customer Segmentation
- Churn Rate Analysis
- Cohort Analysis
- Comparative Analysis 

# Data Visualization
- Built interactive Tableau dashboards to visualize customer churn trends
- Created stacked bar chart showing churn rate by customer tenure
- Created bar chart showing churn rate by payment methods
- Created horizontal bar chart showing churn rate by contract type
- Used filters and dashboards to explore customer segments and churn behavior

# Skills
- Exploratory Data Analysis (EDA)
- Customer Churn Analysis
- Customer Segmentation
- Cohort Analysis
-  Business Analytics
- Descriptive Analytics
- Data Storytelling
- Business Insights
- Decision Support
- Stakeholder Reporting
- Problem Solving


