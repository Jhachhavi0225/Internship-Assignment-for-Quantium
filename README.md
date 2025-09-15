# 🛒 Walmart Sales Data Analysis | 
<img width="1008" height="567" alt="Screenshot 2025-09-09 130636" src="https://github.com/user-attachments/assets/2e8eaca0-990f-4aae-be8d-29b1599b8b9f" />


## 📖 Overview
This project is an in-depth *SQL data analysis* of Walmart's retail sales data. The objective was to transform raw sales data into meaningful insights to understand sales performance, customer behavior, and product trends across different branches and time periods.

---
## 🎯 Business Objectives
This analysis aimed to answer key business questions to drive strategic decisions:
- *Performance Analysis:* How do different branches and product lines perform?
- *Customer Insights:* What are the purchasing patterns and preferences of customers?
- *Temporal Trends:* When do sales peak, and how do they trend over time?
- *Strategic Planning:* Which product lines are growing, and which need attention?

---
## 🔧 Tech Stack & Skills
- *Database Management:* MySQL
- *Key SQL Concepts:*
  - Advanced Aggregations (SUM, COUNT, AVG with GROUP BY)
  - Conditional Logic (CASE WHEN statements)
  - Window Functions (ROW_NUMBER(), RANK(), LAG())
  - Common Table Expressions (CTEs) for complex queries
  - Date and Time Functions (YEAR(), MONTH(), HOUR())
  - Joins and Subqueries

---
## 📊 Dataset Overview
The analysis uses the walmartsalesdata table, which includes:
- *Invoice ID:* Unique identifier for each transaction
- *Branch:* City branch (A, B, C)
- *City:* Location of sale (Yangon, Mandalay, Naypyitaw)
- *Product Line:* Category of product sold (e.g., Electronics, Fashion)
- *Unit Price, Quantity, Total, Gross Income:* Financial metrics
- *Date & Time:* Transaction timestamp
- *Payment Method:* Cash, Ewallet, Credit card

(Note: This is a public dataset used for practice purposes.)

---
## 📈 Key Insights & Findings

---
### 1. Branch Performance
- Branch C is the top performer, contributing *34.24%* of total sales.
- All three branches (A, B, C) show remarkably balanced revenue distribution.

---
### 2. Product Line Analysis
- *Home and Lifestyle* products generate the highest average gross income per transaction.
- *Health and Beauty* showed the highest Month-over-Month (MoM) growth (*+24.7%*) in March 2019.

---
### 3. Sales Trends
- *Peak Sales Hours:* Vary by branch (1 PM for Branch C, 5 PM for Branch B).
- *Transaction Value:* The majority of transactions (*565*) were classified as "Medium" value (₹100 - ₹500).

---
### 4. Customer Behavior
- The top-spending customer in the *Fashion Accessories* category spent *₹1,042.60*.
- *Ewallets* are the most popular payment method in Yangon and Mandalay, while *Cash* is preferred in Naypyitaw.

---
## Conclusion & Business Impact
This analysis provides a clear actionable roadmap:
-  *Resource Allocation*: Balance inventory and staff based on branch performance and peak hours.
-  *Marketing Strategy*: Focus promotions on high-growth product lines like Health and Beauty.
-  *Customer Experience*: Promote Ewallet usage in Naypyitaw to streamline checkout.

*The insights derived help in understanding sales dynamics and making data-driven decisions to enhance profitability and operational efficiency*. 

---
## 👩‍💻 Developed by *Jhachhavi*
      Data Analyst | Visual Storyteller 
---

                                                                                    
