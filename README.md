# 🛒 Supermarket Sales Analysis Dashboard – Power BI

## 📊 Project Overview

This project presents an interactive **Supermarket Sales Dashboard** developed using **Microsoft Power BI**. The dashboard is designed to analyze supermarket sales performance, customer characteristics, product performance, payment methods, and profitability.

The project uses supermarket transaction data containing information about sales transactions, customers, products, payment methods, revenue, gross income, and customer ratings.

The dashboard provides an overview of key business metrics and allows users to explore sales performance through interactive filters and visualizations.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze overall supermarket sales performance.
- Monitor total orders and quantity sold.
- Analyze revenue, net revenue, and profit.
- Identify cities with the highest profit.
- Analyze revenue based on payment methods.
- Compare sales performance across product lines.
- Analyze customer distribution based on customer type.
- Analyze customer ratings for each product line.
- Identify sales trends over time.
- Provide an interactive dashboard for business performance monitoring.

---

## 📁 Dataset

The dataset used in this project was obtained from Kaggle:

**Supermarket Sales Dataset**  
Source: Fares Ashraf – Kaggle

The dataset contains supermarket transaction records from three cities in Myanmar: Yangon, Naypyitaw, and Mandalay.

The dataset consists of **1,000 transaction records and 17 attributes**.

### Dataset Features

| Column | Description |
|---|---|
| Invoice ID | Unique identifier for each transaction |
| Branch | Supermarket branch |
| City | City where the branch is located |
| Customer Type | Type of customer: Member or Normal |
| Gender | Customer gender |
| Product Line | Product category |
| Unit Price | Price per unit |
| Quantity | Number of products purchased |
| Tax 5% | Tax amount calculated at 5% |
| Total | Total transaction amount including tax |
| Date | Transaction date |
| Time | Transaction time |
| Payment | Payment method used |
| COGS | Cost of goods sold |
| Gross Margin Percentage | Gross margin percentage |
| Gross Income | Income generated from the transaction |
| Rating | Customer rating |

Dataset source:

https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales

---

## 🛠️ Tools Used

- **Microsoft Power BI** – Dashboard development, data analysis, visualization, and DAX calculations
- **Microsoft Excel** – Initial data inspection
- **Kaggle** – Dataset source
  
---

## 🔄 Data Preparation

Before creating the dashboard, the dataset was prepared and transformed for analysis.

The data preparation process included:

1. Importing the supermarket sales dataset into Power BI.
2. Checking the structure and data types of each column.
3. Cleaning and transforming the dataset using Power Query.
4. Converting the `Date` column into the appropriate date format.
5. Creating calculated measures using DAX.
6. Preparing the data for visualization and dashboard analysis.

---

## 📌 Key Performance Indicators

The dashboard provides several key performance indicators (KPIs):

| KPI | Value |
|---|---:|
| Total Orders | 1,000 |
| Quantity Sold | 5,510 |
| Revenue | $307.59K |
| Net Revenue | $322.97K |
| Profit | $15.38K |

These KPIs provide a quick overview of the supermarket's overall sales performance.

---

## 📈 Dashboard Features

### 1. Sales Trend Analysis

A time-series visualization is used to analyze **Gross Income** over time based on:

- Year
- Quarter
- Month
- Day

This visualization helps identify fluctuations and trends in supermarket income throughout the sales period.

### 2. Profit by City

The dashboard compares profit generated across the three cities:

- Naypyitaw
- Yangon
- Mandalay

This visualization helps identify which city contributes the most to overall profitability.

### 3. Revenue by Payment Method

Revenue is analyzed based on different payment methods:

- Cash
- Ewallet
- Credit Card

This provides insight into customer payment preferences and their contribution to total revenue.

### 4. Rating by Product Line

Customer ratings are compared across different product lines:

- Food and Beverages
- Fashion Accessories
- Health and Beauty
- Electronic Accessories
- Sports and Travel
- Home and Lifestyle

This analysis helps identify which product categories receive better customer satisfaction ratings.

### 5. Orders by Customer Type

The dashboard compares the number of orders from:

- Member customers
- Normal customers

This provides an overview of customer composition and membership participation.

### 6. Product Line Performance

A detailed table is included to compare product line performance based on:

- Revenue
- Tax
- Net Revenue
- Profit
- Gross Profit Margin (GPM)

This allows users to compare financial performance across product categories.

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to filter the analysis based on:

- **Month**
- **Gender**

Users can select specific categories to dynamically update the dashboard visualizations.

---

## 📊 Dashboard Preview

![Supermarket Sales Dashboard](images/supermarket-sales-dashboard.png)

---
## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Refresh the data if necessary.
4. Use the **Month** and **Gender** slicers to filter the dashboard.
5. Explore the KPIs and visualizations to analyze supermarket sales performance.

---

## 📂 Project Structure

```text
Supermarket-Sales-PowerBI/
│
├── README.md
│
├── dashboard/
│   └── Supermarket-Sales-Dashboard.pbix
│
├── images/
│   └── supermarket-sales-dashboard.png
│
└── dataset/
    └── supermarket_sales.csv
```
## 💡 Key Insights

The dashboard enables users to:

- Monitor overall supermarket sales performance through KPI cards.
- Compare profitability across different cities.
- Understand customer payment preferences.
- Evaluate product line performance based on revenue and profit.
- Compare customer satisfaction across product lines.
- Analyze purchasing behavior between Member and Normal customers.
- Monitor sales trends over time.

## 📚 Data Source

**Supermarket Sales Dataset – Kaggle**

Dataset: https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales

## ⭐ Project Purpose

This project was developed as a **Data Analytics portfolio project** to demonstrate practical skills in:

- Data Analysis
- DAX
- Data Visualization
- Dashboard Development
- Business Intelligence
- Power BI

