# 📊 Superstore Sales — Exploratory Data Analysis

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on Superstore sales data using Python to identify sales patterns, trends, product performance, regional differences, customer segment behavior, and shipping insights.

## 🎯 Objectives

- Understand the structure and quality of the dataset
- Clean and prepare the data for analysis
- Analyze sales distribution and outliers
- Identify sales trends over time
- Compare categories and sub-categories
- Analyze regional and customer segment performance
- Identify top-performing products
- Analyze shipping modes and shipping duration
- Generate meaningful business insights

## 📊 Dataset

- **Records:** 9,800
- **Original columns:** 18
- **Final analytical columns:** 19
- **Order period:** 2015–2018
- **Unique Orders:** 4,922
- **Unique Customers:** 793
- **Unique Products:** 1,861

## 🧹 Data Cleaning

The project includes:

- Missing-value analysis
- Duplicate-row verification
- Date conversion
- Postal Code correction
- Data-type validation
- Shipping Days calculation
- Negative shipping-duration validation
- Sales outlier detection using the IQR method

The dataset initially contained **11 missing Postal Codes**. These were handled and Postal Code was converted into string format. After cleaning, **0 missing values and 0 completely duplicated rows** remained. :contentReference[oaicite:2]{index=2}

## 🔎 Analysis Performed

- Sales Distribution
- Sales by Category
- Sales by Sub-Category
- Sales by Region
- Sales by Customer Segment
- Yearly Sales Trends
- Monthly Sales Trends
- Top Products by Sales
- Frequently Ordered Products
- Average Sales by Product
- Sales by Shipping Mode
- Shipping Days Analysis
- Sales vs Shipping Days
- Region × Category Analysis
- Monthly Category Performance

## 💡 Key Insights

- **Technology** generated the highest total sales among the three major categories.
- **Phones** generated the highest total sales among sub-categories, while **Fasteners** generated the lowest.
- **West** had the highest total regional sales.
- **Consumer** generated the highest total sales among customer segments.
- **Canon imageCLASS 2200 Advanced Copier** was the top product by total sales.
- **November and December** showed strong sales performance.
- Most orders were shipped within approximately **4 days**, with shipping duration ranging from **0–7 days**.
- Sales were strongly right-skewed, with genuine high-value transactions appearing as potential outliers.
- Shipping duration did not show a clear direct pattern with average sales.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

```text
codealpha-superstore-visualization/
│
├── Superstore_EDA.ipynb
├── Superstore_Cleaned.csv
└── README.md
