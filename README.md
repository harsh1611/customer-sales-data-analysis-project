md

📊 Customer Sales Data Analysis Project

A complete end-to-end Data Analysis Project using Python, Pandas, Matplotlib, and Seaborn.
This project analyzes customer orders, product categories, regions, and revenue trends using a small sample dataset.

🔍 Project Overview

This project includes:

Data Loading & Cleaning

Feature Engineering

Exploratory Data Analysis (EDA)

KPI Calculation

Visualizations

Pivot Tables

Customer-Level Analytics

RFM (Recency, Frequency, Monetary) Segmentation

📁 Project Structure
customer-sales-data-analysis-project/
│
├── data/
│   └── orders_raw.csv
│
├── notebooks/
│   └── data_analysis_notebook.ipynb
│
├── outputs/
│   ├── orders_cleaned.csv
│   ├── pivot_revenue_by_category_region.csv
│   ├── customer_stats.csv
│   └── customer_rfm.csv
│
└── README.md

📚 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📊 Key Insights

✔ North region has the highest number of orders
✔ Electronics category generates the highest revenue
✔ Customer C001 is the top customer
✔ High-value transactions can be identified using median split
✔ RFM model helps understand customer behavior

▶️ How to Run

Clone the repo:

git clone https://github.com/yourusername/customer-sales-data-analysis-project.git


Open Jupyter Notebook:

jupyter notebook


Run:

notebooks/data_analysis_notebook.ipynb

📄 Dataset Description

The dataset includes:

Column	Description
OrderID	Unique order number
CustomerID	Customer identifier
OrderDate	Date of order
ProductCategory	Category like Electronics, Books
ProductName	Item purchased
Quantity	Units ordered
UnitPrice	Price per unit
TotalPrice	Quantity × UnitPrice
Region	North, South, East, West
🧑‍💻 Author

Harsh Lalakiya
Data Researcher | Aspiring Data Analyst
