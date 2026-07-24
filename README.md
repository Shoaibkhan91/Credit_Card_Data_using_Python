#  Credit Card Customer Analytics using Python

##  Project Overview

This project focuses on analyzing credit card customer behavior using Python to gain insights into customer spending, repayment patterns, profitability, and business performance. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, and customer segmentation to support data-driven decision-making in the banking industry.

---

##  Business Objective

The objective of this project is to help the bank understand customer spending and repayment behavior by analyzing transaction data and generating actionable business insights.

Key business questions addressed include:

- Customer spending analysis
- Customer repayment analysis
- Monthly profitability
- Product performance
- City-wise customer behavior
- Age group spending analysis
- Customer ranking based on repayment
- Banking KPI reporting

---

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Dataset

The project uses three datasets:

- **Customer Acquisition** – Customer demographic and credit limit information
- **Spend** – Customer transaction records
- **Repayment** – Customer repayment history

---

##  Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Replaced customer age below 18 years with the average age.
- Capped transaction amounts exceeding the customer's credit limit at 50% of the limit.
- Limited repayment amounts exceeding the customer's credit limit to the maximum allowed limit.
- Checked missing values and duplicate records.
- Converted date columns into datetime format.
- Merged multiple datasets for comprehensive analysis.

---

##  Exploratory Data Analysis (EDA)

The following analyses were performed:

###  Customer Analysis

- Total Customers
- Customer Distribution
- Customer Age Analysis
- Customer Segmentation
- Top 10 Customers by Repayment
- Customer Spending Behavior

---
###  Spending Analysis

- Monthly Spending Trend
- Average Monthly Spend
- City-wise Spending
- Product-wise Spending
- Yearly Spending Analysis
- Highest Spending City
- Age Group-wise Spending

---

###  Repayment Analysis

- Average Monthly Repayment
- Customer Repayment Trends
- Top 10 Customers by Repayment
- Product-wise Repayment Analysis

---

###  Profitability Analysis

Calculated monthly bank profit using:

- Monthly Spend
- Monthly Repayment
- Monthly Profit
- Interest Earned (2.9% per month on positive profit)

---

###  Product Analysis

- Top 5 Product Types
- Product-wise Spend
- Product Performance Comparison
- Monthly Product Trends

---

###  City-wise Analysis

- Customer Distribution
- Total Spending
- Product-wise Spending
- Yearly Spending Trends

---

##  Data Visualization

Created multiple visualizations including:

- Monthly Spend Trend
- Monthly Repayment Trend
- City-wise Spend Comparison
- Product-wise Spending
- Yearly Air Ticket Spend
- Monthly Product Spend Trends
- Customer Spending by Age Group
- Top Customers by Repayment

---

##  User Defined Python Function

Developed a reusable Python function to identify the **Top 10 Customers** based on repayment.

The function allows users to filter by:

- Product Type (Gold / Silver / Platinum)
- Time Period (Monthly / Yearly)

This makes the analysis dynamic and reusable.

---

##  Key Business Insights

- Identified the highest spending customers.
- Determined the top repayment customers.
- Analyzed city-wise spending behavior.
- Measured monthly profitability for the bank.
- Evaluated product performance.
- Compared spending patterns across age groups.
- Identified seasonal trends in customer spending.

---

##  Project Structure

```
Credit-Card-Customer-Analytics

 Dataset
    Customer_Acquisition.xlsx
    Spend.xlsx
    Repayment.xlsx

 Notebook
  redit_Card_Customer_Analytics.ipynb





2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells to reproduce the analysis.

---

##  Skills Demonstrated

- Python
- Pandas
- NumPy
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Analytics
- Banking Analytics
- Financial Analytics
- Business Intelligence
- Feature Engineering
- Python Functions
- KPI Reporting

---

##  Learning Outcomes

Through this project, I gained practical experience in:

- Customer Analytics
- Banking Data Analysis
- Financial KPI Analysis
- Data Cleaning & Transformation
- Customer Segmentation
- Business Intelligence
- Python Programming
- Exploratory Data Analysis
- Data Visualization
- Writing reusable Python functions

---

##  Author

**Shoaib Khan**

 Email: SHOAIB913599@gmail.com

 LinkedIn: https://www.linkedin.com/in/shoaib-khan-1b16232b2

 GitHub: https://github.com/your-github-username

---

##  Support

If you found this project useful, please consider giving it a  Star on GitHub.

---

###  Keywords

Python, Pandas, NumPy, Data Analysis, Customer Analytics, Credit Card Analytics, Banking Analytics, Financial Analytics, Data Visualization, EDA, Business Intelligence, Customer Segmentation, KPI Dashboard, Jupyter Notebook.
