# Customer Behaviour Analysis

## Overview

This project analyzes customer shopping behaviour using Python, SQL Server, and Power BI. The workflow includes data cleaning, exploratory data analysis (EDA), SQL-based business analysis, dashboard creation, and reporting.

The goal of the project is to identify customer purchasing patterns, subscription behaviour, revenue trends, and product performance.

---

## Dataset

* Dataset: Customer Shopping Behaviour Dataset
* Format: CSV
* Records include:

  * Customer demographics
  * Purchase amount
  * Product category
  * Review ratings
  * Shipping type
  * Discount usage
  * Subscription status
  * Previous purchases

---

## Tools & Technologies

* Python
* Pandas
* SQL Server
* SQLAlchemy
* Power BI
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Loaded the dataset into Python using Pandas.
* Connected Python with SQL Server using SQLAlchemy.

### 2. Data Cleaning

* Checked missing values and data types.
* Removed inconsistencies and prepared the dataset for analysis.
* Created derived fields such as customer segments and age groups.

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

* Customer demographics
* Purchase behaviour
* Product categories
* Discounts and subscriptions
* Revenue trends

### 4. SQL Analysis

Business questions were solved using SQL queries in SQL Server.

Some key analyses include:

* Revenue comparison by gender
* Average spending of subscribed vs non-subscribed customers
* Top-rated products
* Discount usage analysis
* Customer segmentation
* Top purchased products by category
* Revenue contribution by age group

---

## Power BI Dashboard

The dashboard was built in Power BI to visualize customer purchasing patterns, category performance, subscription behaviour, and revenue insights.

### Dashboard Preview

![Customer Behavior Dashboard](https://github.com/muhammed-swalih296/Customer_Behaviour_Analysis/blob/main/Screenshot%202026-05-21%20124601.png)

### KPI Cards

![Dashboard KPIs](https://github.com/muhammed-swalih296/Customer_Behaviour_Analysis/blob/main/Screenshot%202026-05-21%20125159.png)

### Dashboard Features

* KPI cards for total customers, average purchase amount, and review ratings
* Revenue analysis by category
* Sales analysis by category
* Customer segmentation by age group
* Subscription status analysis
* Interactive slicers for:

  * Gender
  * Category
  * Subscription status
  * Shipping type

### Key Dashboard Metrics

* Total Customers: 3.9K
* Average Purchase Amount: $59.76
* Average Review Rating: 3.75

---

## Key Insights

* Subscription customers showed higher average spending.
* Certain products received consistently higher ratings.
* Discount usage influenced purchasing behaviour.
* Returning and loyal customers contributed a significant share of revenue.

---

## Project Structure

```text
Customer_Shopping_Behaviour_Analysis/
│
├── Customer_Shopping_Behaviour_Analysis.ipynb
├── customer.sql
├── dashboard.pbix
├── report.pdf
└── README.md
```

---

## How to Run

### Python Analysis

1. Open the Jupyter Notebook.
2. Install required libraries:

```bash
pip install pandas sqlalchemy
```

3. Run the notebook cells sequentially.

### SQL Analysis

1. Open SQL Server Management Studio (SSMS).
2. Import the dataset into SQL Server.
3. Run the queries from `customer.sql`.

### Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the dataset connection if needed.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* SQL Query Writing
* Customer Segmentation
* Business Insight Generation
* Dashboard Development
* Data Visualization

---

## Author

Muhammed Swalih
