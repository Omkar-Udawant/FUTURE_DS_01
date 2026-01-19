# 📊 Business Sales Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Domain](https://img.shields.io/badge/Domain-Data%20Science%20%26%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Internship](https://img.shields.io/badge/Internship-Future%20Interns-purple)

## 🚀 Project Overview

This project is developed as part of my Data Science & Analytics Internship at Future Interns. The goal is to analyze business sales data and design a professional, interactive Power BI dashboard that helps stakeholders understand performance trends and make data-driven decisions. The dashboard emphasizes business storytelling and actionable insights.
-----


## 🛠️ Tool | Power BI  
## 🌐 Domain | Data Science & Analytics  
## 🚀 Project | Completed  
## 🏢 Internship | Future Interns


-----
Business Sales Dashboard | Power BI
Project Overview

This project is developed as part of my Data Science & Analytics Internship at Future Interns. The aim is to analyze business sales data and design a professional, interactive Power BI dashboard that helps stakeholders understand performance, trends, and opportunities.

The dashboard is all about business storytelling, allowing managers and decision-makers to take data-driven actions rather than just looking at numbers.

Business Objectives

This dashboard answers key business questions such as:

What is the overall revenue, profit, and order volume?

How do sales and profits trend over time?

Which categories and sub-categories drive the most revenue?

Which regions and states perform best?

How does sales compare with profit across categories?

Which customer segments contribute the most revenue?

## 🖼️ Dashboard Pages Overview

### 🔹 Page 1: Sales Performance Overview
![Page 1 Dashboard](https://github.com/Omkar-Udawant/FUTURE_DS_01/blob/main/Screenshots/PAGE1.png)

This page gives top-level management a quick snapshot of business performance.

Key Visuals & KPIs:

Total Revenue

Number of Orders

Net Profit

Units Sold

Average Order Value (AOV)

Monthly Revenue and Profit Trends by Year

Category-wise Revenue Share

Regional Revenue Distribution

Year Slicer for dynamic filtering

### 🔹 Page 2: Detailed Sales & Profit Analysis
![Page 2 Dashboard](https://github.com/Omkar-Udawant/FUTURE_DS_01/blob/main/Screenshots/PAGE2.png)

This page is for business analysts and operations teams to dive deeper into the data.

Key Visuals:

Top States by Revenue

Revenue Contribution by Customer Segment

Geographic Distribution of Revenue (U.S.)

Revenue Trend Over Time (Daily Granularity)

## 📊 Key Visuals & KPIs
- **Total Revenue:** Overall revenue generated.
- **Profit Margin:** Calculated as total profit divided by total sales.
- **Category Performance:** Highlights top-selling product categories.

Tools & Technologies Used

Power BI Desktop – Dashboard creation & visualization

Python (Pandas) – Data cleaning & preprocessing

CSV / Excel Dataset

DAX (Data Analysis Expressions) – KPI calculations



## 🧩 Key DAX Measures Used
Total Revenue = SUM(Sales[Sales])
Total Orders = DISTINCTCOUNT(Sales[Order_ID])
Net Profit = SUM(Sales[Profit])
Units Sold = SUM(Sales[Quantity])
AOV = DIVIDE([Total Revenue], [Total Orders])

Dashboard Design & Theme

Dark Mode dashboard for a premium, modern look

Clean and minimal layout for better readability

Consistent color palette across all visuals

Focus on clarity, insights, and decision-making

## 📂 Repository Structure
- **`Dashboard/`**: Contains the Power BI `.pbix` file.
- **`Dataset/`**: Includes the dataset used (if applicable).
- **`Screenshots/`**: Screenshots of the dashboard pages.
- **`README.md`**: This file.

## 🔍 Key Insights and Findings
- The South region outperformed other regions in total sales.
- Technology products were the highest contributors to revenue.
- Seasonal trends were observed, with Q3 showing peak sales.

## 🙏 Acknowledgements
Special thanks to Future Interns for their support and guidance throughout this project.

## ✍️ Author
Omkar Udawant

---
