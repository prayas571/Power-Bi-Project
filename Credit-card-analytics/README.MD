📊 Credit Card Analytics – Power BI Dashboard
(End-to-End BI Project | Data Modeling | DAX | Customer & Transaction Insights)
🚀 Project Summary

This project presents a comprehensive Credit Card Analytics System built using Power BI, designed to help financial institutions understand transaction behavior, customer demographics, revenue patterns, and business performance.

The solution contains two dashboards:

1️⃣ Credit Card Transaction Report
2️⃣ Credit Card Customer Report

Both dashboards are carefully designed with rich visuals, DAX-driven metrics, and deep business insights.

🖼️ Dashboard Previews
1️⃣ Credit Card Transaction Report

This dashboard provides a detailed view of the overall credit card transactional performance.

Key Features

✔️ Total Revenue, Total Interest, Transaction Count, Transaction Amount

✔️ Revenue breakdown by Card Category (Blue, Silver, Gold, Platinum)

✔️ Quarterly Revenue & Transaction Trend

✔️ Revenue by Expenditure Type (Bills, Travel, Entertainment, etc.)

✔️ Revenue by Customer Occupation & Education

✔️ Customer Acquisition Cost (CAC)

✔️ Interactive filters for Quarter & Week Start Date

2️⃣ Credit Card Customer Report

This dashboard focuses on customer-level insights to support segmentation and marketing strategy.

Key Features

✔️ Total Revenue, Total Income, Customer Satisfaction Score (CSS)

✔️ Revenue trends by Gender

✔️ Revenue Analysis by Age Group, Education Level, Marital Status, Dependents

✔️ Customer Job vs Revenue

✔️ Top 5 States by Revenue

✔️ Salary Group Insights

✔️ Card Category Comparisons

📁 Folder Structure
credit-card-analytics-powerbi/
│
├── PowerBI/
│   ├── CreditCard_Transaction_Report.pbix
│   └── CreditCard_Customer_Report.pbix
│
├── Images/
│   ├── transaction_dashboard.png
│   └── customer_dashboard.png
│
└── README.md

📊 KPIs & DAX Measures
Primary KPIs

Total Revenue

Total Interest

Customer Satisfaction Score (CSS)

Total Income

Transaction Count

Transaction Amount

Customer Acquisition Cost (CAC)

Examples of DAX Used
Total Revenue = SUM(Transactions[Revenue])

Total Interest = SUM(Transactions[Interest_Earned])

Transaction Count = COUNTROWS(Transactions)

CSS = AVERAGE(Customers[Customer_Satisfaction_Score])

💡 Key Insights From the Analysis
🔷 Transaction Insights

Blue and Silver cards generate the highest revenue.

Highest revenue recorded in Q2 due to heavy customer spending.

Bills, Entertainment, and Travel are the top spending categories.

Businessmen and White-collar professionals drive major revenue.

🔷 Customer Insights

Male customers generate slightly higher revenue.

Age group 40–50 contributes the most to total revenue.

Graduate and Post-Graduate customers generate the highest revenue.

Married customers show more spending power than single customers.

High-income customers drive premium card revenue.

🛠️ Tools & Technologies Used
Area	Tools
Data Visualization	Power BI Desktop
Data Cleaning	Power Query (ETL)
Data Modeling	Star Schema, Fact & Dimension Tables
DAX Calculations	Measures, Time Intelligence
Data Source	Excel / CSV
⭐ Business Applications

This dashboard can be used by banks or credit card companies for:

Customer segmentation

Marketing campaign targeting

Product performance analysis

Risk evaluation and fraud monitoring

Revenue optimization

Strategic decision-making
