# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, revenue drivers, customer segments, and other business insights.

The analysis combines **Python, Pandas, SQL, SQLite, and data visualization** to transform raw customer shopping data into meaningful analytical insights.

---

## 🎯 Objectives

The main objectives of this project are to:

* Clean and prepare customer shopping data
* Handle missing values and improve data consistency
* Create useful customer-level analytical features
* Store and analyze the processed data using SQLite
* Use SQL queries to analyze purchasing behavior
* Identify revenue and purchase patterns across different customer segments
* Analyze categories, products, locations, subscriptions, payment methods, discounts, and purchasing frequency
* Calculate key performance indicators (KPIs)
* Visualize important findings

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* SQLite
* SQL
* Matplotlib
* Jupyter Notebook
* Google Colab

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Cleaning
     ↓
Missing Value Treatment
     ↓
Feature Engineering
     ↓
SQLite Database
     ↓
SQL Analysis
     ↓
KPI Analysis
     ↓
Data Visualization
     ↓
Business Insights
```

---

## 🧹 Data Preparation

The project performs several data preparation steps, including:

* Loading the dataset using Pandas
* Inspecting the dataset structure
* Generating summary statistics
* Checking for missing values
* Imputing missing review ratings using category-level median values
* Standardizing column names using snake_case
* Creating customer age groups
* Converting purchasing frequency into a numeric day-based representation
* Removing redundant columns

---

## 🗄️ SQL & SQLite Analysis

The cleaned dataset is loaded into a SQLite database for SQL-based analysis.

The analysis includes:

* Purchase volume by category
* Revenue by category
* Average purchase amount by category
* Gender-based purchasing analysis
* Subscription status analysis
* Seasonal purchasing analysis
* Location-based revenue analysis
* Top purchased items
* Item-level revenue analysis
* Review rating analysis
* Discount analysis
* Payment method analysis
* Shipping type analysis
* Purchasing frequency analysis
* Age-group analysis
* Previous purchase analysis

---

## 📊 Visualizations

The project includes visualizations for:

* Total purchases by category
* Total revenue by category
* Top 10 most purchased items
* Top 10 locations by revenue
* Purchases by age group
* Purchases by subscription status
* Purchases by payment method
* Purchases with and without discounts

---

## 📈 KPI Analysis

The project calculates key business metrics including:

* Total Transactions
* Total Customers
* Total Revenue
* Average Purchase Amount
* Average Review Rating

It also identifies high-performing categories, locations, and subscription segments.

---

## 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Customer-Shopping-Behavior-Analysis.git
```

### 2. Navigate to the project

```bash
cd Customer-Shopping-Behavior-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open:

```text
Customer_Shopping_Behavior_Analysis.ipynb
```

---

## 💡 Key Skills Demonstrated

This project demonstrates practical experience with:

**Python | Pandas | SQL | SQLite | Data Cleaning | Feature Engineering | Exploratory Data Analysis | KPI Analysis | Data Visualization | Business Analytics**

---

## 👤 Author

**Piyansu Das**

If you find this project useful, feel free to ⭐ the repository.
