📊 Business Sales Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Domain](https://img.shields.io/badge/Domain-Data%20Science%20%26%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Internship](https://img.shields.io/badge/Internship-Future%20Interns-purple)






🚀 Project Overview

This project was developed as part of my Data Science & Analytics Internship at Future Interns.
The objective was to analyze business sales data and design a professional, interactive Power BI dashboard that enables stakeholders to understand performance, identify trends, and make data-driven decisions.

The dashboard focuses on business storytelling, transforming raw data into actionable insights rather than just numbers.

🛠️ Tools & Technologies

Power BI Desktop – Dashboard design & visualization

Python (Pandas) – Data cleaning & preprocessing

DAX (Data Analysis Expressions) – KPI calculations

CSV / Excel – Dataset format

🎯 Business Objectives

This dashboard answers key business questions such as:

What is the overall revenue, profit, and order volume?

How do sales and profits trend over time?

Which categories and sub-categories generate the most revenue?

Which regions and states perform best?

How does sales compare with profit across categories?

Which customer segments contribute the most revenue?

🖼️ Dashboard Pages Overview
🔹 Page 1: Sales Performance Overview

Purpose:
Provides top-level management with a quick snapshot of overall business performance.

Key KPIs & Visuals:

Total Revenue

Total Orders

Net Profit

Units Sold

Average Order Value (AOV)

Monthly Revenue & Profit Trends (Year-wise)

Category-wise Revenue Share

Regional Revenue Distribution

Year slicer for dynamic filtering

🔹 Page 2: Detailed Sales & Profit Analysis

Purpose:
Designed for analysts and operations teams to explore deeper insights.

Key Visuals:

Top States by Revenue

Revenue by Customer Segment

Geographic Revenue Distribution (U.S. Map)

Daily Revenue Trend Analysis

📊 Key KPIs Explained

Total Revenue: Total sales generated

Total Orders: Unique order count

Net Profit: Total profit earned

Units Sold: Total quantity sold

Average Order Value (AOV): Revenue per order

🧮 Key DAX Measures
Total Revenue = SUM(Sales[Sales])
Total Orders = DISTINCTCOUNT(Sales[Order_ID])
Net Profit = SUM(Sales[Profit])
Units Sold = SUM(Sales[Quantity])
AOV = DIVIDE([Total Revenue], [Total Orders])

🎨 Dashboard Design & Theme

Dark mode dashboard for a premium, modern look

Clean and minimal layout for better readability

Consistent color palette across visuals

Designed with a strong focus on clarity, insights, and decision-making

📂 Repository Structure
├── Dashboard/      # Power BI (.pbix) file
├── Dataset/        # Dataset used
├── Screenshots/    # Dashboard screenshots
└── README.md       # Project documentation

🔍 Key Insights & Findings

The South region outperformed other regions in total sales

Technology products were the highest revenue contributors

Seasonal trends observed, with peak sales in Q3

🙏 Acknowledgements

Special thanks to Future Interns for their guidance and support throughout this internship project.

✍️ Author

Omkar Udawant
