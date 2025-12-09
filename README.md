# 📊 E-Commerce Sales Analysis & Customer Segmentation
(Python • Pandas • NumPy • Seaborn • Matplotlib • Scikit-Learn)

This project analyzes an E-Commerce dataset to uncover insights about sales, profit, discounts, customer behavior, and product performance. It also includes customer segmentation using clustering to support data-driven marketing and business decisions.

# 🚀 Project Overview

Performed data cleaning, feature engineering, and exploratory data analysis (EDA).

Analyzed sales & profit trends, discount impact, top categories, states, and customer patterns.

Built RFM (Recency, Frequency, Monetary) metrics and applied K-Means clustering to segment customers.

Generated insights to improve marketing strategy, product targeting, and profitability.

## 🧹 1. Data Cleaning & Preprocessing

Fixed missing values and corrected data types.

Cleaned date columns and extracted additional time-based features:

Order Year, Order Month, Order Month Name

Ship Year, Ship Month, Ship Month Name

Day-of-week columns

Removed duplicates and prepared the dataset for EDA and modeling.

## 📈 2. Exploratory Data Analysis (EDA)
🔸 Sales & Profit Analysis

Month-wise sales trends

Year-wise profitability

Best & worst performing months

🔸 Category & Sub-Category Performance

Top 10 profitable states

Profitability by segment & product category

Discount impact on loss-making vs profitable products

🔸 Customer Insights

Spending patterns

Order frequency

Distribution of high-value buyers

Visualizations Used:
Bar charts, line plots, scatter plots, heatmaps, treemaps (Plotly), pair plots.

## 🤖 3. Customer Segmentation (K-Means Clustering)
Features Used (RFM Model)

Recency – Days since last purchase

Frequency – Total number of orders

Monetary – Total spending

Steps

RFM Feature Engineering

Data Scaling with StandardScaler

Elbow Method to find optimal K

K-Means clustering

Visualization & interpretation of cluster results

## 🧩 4. Cluster Interpretation
### 🟩 Cluster 0 — High Value Customers

Highest spending

Frequent shoppers

Recent purchases

Strategy: Exclusive offers, premium loyalty programs

### 🟦 Cluster 1 — Medium Value Customers

Moderate spending

Steady frequency

Strategy: Upsell/Cross-sell to increase revenue

### 🟧 Cluster 2 — Low Value Customers

Low orders & low spending

Strategy: Awareness campaigns, entry-level offers

### 🟥 Cluster 3 — At-Risk Customers

Long recency

Very low monetary value

Strategy: Re-engagement campaigns, reminders, coupons

## 🎯 5. Key Business Insights

Technology is the top profit-generating category.

Some sub-categories (e.g., Tables, Supplies) turn unprofitable with discounts.

Certain states consistently lead in revenue and profitability.

Customer segmentation reveals four clear personas for targeted marketing.

## 🛠️ 6. Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Jupyter Notebook

## 📂 7. Repository Structure

📁 E-Commerce-Segmentation
│── 📄 E-Commerce_project.ipynb
│── 📄 README.md
│── 📁 data (optional)
     └── Sample-Superstore.csv

