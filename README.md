# Ecommerce-sales-customer-analysis
End-to-end data analysis of 500K+ e-commerce transactions using Python, Pandas, NumPy, Matplotlib &amp; Seaborn — covering sales, product, customer, and time-based insights.

# E-Commerce Sales & Customer Behavior Analysis

A comprehensive data analysis project exploring sales trends, product performance, and customer behavior using a real-world e-commerce transactional dataset.

## 📌 Project Overview

Analyzed 500,000+ e-commerce transactions to uncover sales patterns, identify top-performing products, understand customer purchasing behavior, and detect seasonal trends. This project demonstrates end-to-end data analysis — from data cleaning to business insight generation.

## 🎯 Objectives

- Calculate overall revenue and monthly sales trends
- Identify best and worst performing products
- Analyze customer purchase behavior (repeat vs one-time buyers)
- Discover seasonality and day-wise sales patterns
- Visualize all findings through 10+ charts

## 🛠️ Technologies Used

- **Python** — Core programming
- **Pandas** — Data cleaning, transformation, and groupby analysis
- **NumPy** — Statistical calculations
- **Matplotlib** — Data visualization
- **Seaborn** — Advanced visualizations and heatmaps

## 📊 Analysis Performed

### 1. Sales Analysis
- Total revenue calculation
- Month-wise revenue trend
- Best and worst performing months
- Daily average sales

### 2. Product Analysis
- Top 10 best-selling products (by quantity and revenue)
- Bottom 10 underperforming products
- Highest revenue-generating product

### 3. Customer Analysis
- Top 10 highest-spending customers
- Repeat vs one-time customer segmentation
- Average customer order frequency
- Country-wise customer distribution

### 4. Time-Based Analysis
- Day-of-week sales patterns
- Seasonal trends (peak sales months)
- Year-over-year growth (where applicable)

## 📈 Visualizations Included

1. Monthly Revenue Trend (Line Chart)
2. Top 10 Products by Revenue (Bar Chart)
3. Top 10 Customers (Bar Chart)
4. Country-Wise Sales Distribution (Bar Chart)
5. Day-Wise Sales Pattern (Bar Chart)
6. One-Time vs Repeat Customers (Pie Chart)
7. Order Quantity Distribution (Histogram)
8. Price vs Quantity Relationship (Scatter Plot)
9. Correlation Heatmap
10. Month vs Country Revenue (Pivot Table Heatmap)
11. Bottom 10 Underperforming Products (Bar Chart)

## 🔍 Key Insights

- Identified peak sales season with significantly higher revenue (Nov–Dec)
- A large portion of customers are one-time buyers, highlighting a retention opportunity
- Top 10 products contribute a disproportionate share of total revenue
- Strong correlation found between order quantity and total revenue
- Sales vary notably by day of the week and country

## 📁 Dataset

Online Retail Dataset (UK-based e-commerce transactions)  
Source: Kaggle / UCI Machine Learning Repository
This project uses the Online Retail Dataset.
Download it here: https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset
Place the CSV file in the project folder before running the notebook.

## 🧹 Data Cleaning Steps

- Removed rows with missing Customer IDs
- Removed negative quantity values (returns/cancellations)
- Converted date columns to proper datetime format
- Created a new `TotalPrice` column (Quantity × UnitPrice)

## ▶️ How to Run

1. Clone this repository
2. Install required libraries: "pip install pandas numpy matplotlib seaborn"
3. Open the Jupyter Notebook
4. Run all cells sequentially

## 📌 Future Improvements

- Build a customer segmentation model (RFM Analysis)
- Add sales forecasting using time series techniques
- Create an interactive dashboard using Plotly/Dash

---

⭐ If you found this project helpful, feel free to star this repository!
