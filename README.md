**🛍️ Customer Shopping Behavior Analysis**

End-to-End Data Analytics Project (Python • MySQL• Power BI)

This project is a complete end-to-end analysis of customer shopping behavior using Python, SQL, PostgreSQL, and Power BI.
It covers the full analytics pipeline—data cleaning, feature engineering, database integration, business analysis, and dashboard visualization.
The goal is to understand how customers shop, what influences their purchases, and how businesses can use the insights to improve sales, marketing, and customer retention.

📌 Project Objectives

Analyze customer demographics, spending patterns, and shopping behavior
Identify high-value customers, popular products, and seasonal trends
Compare subscribers vs. non-subscribers
Understand discount dependency and revenue drivers
Build an interactive Power BI dashboard for business decision-making

📂 Dataset Summary

Total Records: 3,900
Columns: 18
Data Includes:
Customer Age, Gender, Location
Purchase Amount, Category, Item Purchased
Discount & Promo Code Usage
Review Rating, Shipping Type
Subscription Status
Previous Purchases & Purchase Frequency
Missing Values: 37 values in Review Rating

🐍 Exploratory Data Analysis (Python)

Performed in Jupyter Notebook
Key steps include:

✔ Data Cleaning
Checked structure using info() and summary statistics using describe()
Imputed missing Review Rating using median rating per product category
Standardized column names into snake_case

✔ Feature Engineering
Created age_group using age bins
Created purchase_frequency_days
Removed redundant fields (promo_code_used)
Added categorical breakdowns for easier segmentation

✔ Database Integration
Connected Python to MySQL
Loaded cleaned dataframe into SQL for deeper business analysis

🛢️ Business Analysis in SQL (MySQL)

Key insights generated:
Revenue by Gender – Identified which customer group contributes more
High-Spending Discount Users – Customers who spend above average even after discounts
Top 5 Products by Average Rating
Shipping Type Comparison – Express vs Standard in terms of spend
Subscribers vs Non-Subscribers – Revenue, average spend, and behavior
Discount-Dependent Products – Products most frequently bought after discounts
Customer Segmentation – New, Returning, and Loyal customers
Top 3 Products per Category
Repeat Buyers & Subscription Likelihood
Revenue by Age Group

📊 Interactive Power BI Dashboard

Created a complete dashboard showcasing:




<img width="1348" height="735" alt="Screenshot 2025-12-11 004326" src="https://github.com/user-attachments/assets/62d2a810-d85b-46f3-a42a-eaa8500c3785" />




Revenue & Sales Overview
Customer Segments
Best-selling Products
Seasonal Purchase Trends
Demographic Insights
Discount vs Non-Discount Purchases
Subscription Impact on Revenue

🎯 Business Recommendations

Based on insights:
Boost Subscriptions by highlighting exclusive benefits
Launch Loyalty Programs for high-frequency & high-spend customers
Optimize Discount Strategy to avoid margin loss
Prioritize Products with Higher Ratings in marketing
Target High-Revenue Age Groups and express-shipping users
