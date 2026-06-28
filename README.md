# 📊 Mastering Sales Using Power BI

<div align="center">

# 📈 End-to-End Sales Analytics & Forecasting System


---

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python)
![SQL](https://img.shields.io/badge/SQL-MySQL-green?style=for-the-badge\&logo=mysql)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge\&logo=powerbi)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)

**Author:** Sanjeev A

</div>

---

# 📸 Project Preview


---



---

# 📖 Overview

Mastering Sales Using Power BI is a comprehensive Business Intelligence and Predictive Analytics project developed to analyze historical sales data, discover hidden business patterns, and forecast future sales 

The project combines relational databases, data preprocessing, statistical analysis, predictive modeling, and interactive visualization into a single business intelligence solution.

The complete workflow includes:

* SQL-based data extraction and transformation
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Interactive Power BI Dashboard
* Business Insights & Decision Support

---

# 🎯 Objectives

* Build an end-to-end Business Intelligence solution.
* Improve sales forecasting using Machine Learning.
* Analyze customer, product, and regional performance.
* Create interactive Power BI dashboards.
* Generate business insights for strategic decision making.

---

# 💡 Problem Statement

Traditional sales forecasting methods often struggle with:

* Large transactional datasets
* Multiple relational tables
* Dynamic market behavior
* Seasonal demand fluctuations
* Manual reporting processes

This project addresses these challenges by integrating Machine Learning with interactive dashboards to provide scalable and data-driven forecasting.

---

# 🏗 Project Architecture

```text
                  Raw Sales Dataset
                         │
                         ▼
                  SQL Data Extraction
                         │
                         ▼
               Data Cleaning & Preprocessing
                         │
                         ▼
              Exploratory Data Analysis (EDA)
                         │
                         ▼
                 Feature Engineering
                         │
                         ▼
               Sales Forecast Generation
                         │
                         ▼
               Interactive Power BI Dashboard
                         │
                         ▼
                Business Decision Making
```

---

# 🛠 Technology Stack

| Technology   | Purpose                          |
| ------------ | -------------------------------- |
| Python       | Data Analysis & Machine Learning |
| SQL          | Data Extraction & Transformation |
| Power BI     | Dashboard & Visualization        |
| Pandas       | Data Processing                  |
| NumPy        | Numerical Computing              |
| Matplotlib   | Data Visualization               |

---

# 📂 Repository Structure

```text
Mastering-Sales-Using-PowerBI-ML
│
├── data
│   ├── raw
│   ├── processed
│
├── notebooks
│   ├── EDA.ipynb
│   ├── Forecasting.ipynb
│
├── sql
│   ├── database.sql
│   ├── queries.sql
│
├── src
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── forecasting.py
│
│
├── dashboard
│   ├── SalesDashboard.pbix
│
├── screenshots
│
├── reports
│
├── requirements.txt
│
├── LICENSE
│
└── README.md
```

---

# 📊 Dataset Description

The project uses five relational tables.

## 1️⃣ Transactions

* order_date
* sales_qty
* sales_amount
* cost_price
* normalized_sales_price
* profit_margin
* customer_code
* product_code
* market_code

---

## 2️⃣ Customers

* customer_code
* customer_name
* customer_type

---

## 3️⃣ Products

* product_code
* product_type

---

## 4️⃣ Markets

* market_code
* market_name
* zone

---

## 5️⃣ Date

* date
* month
* year
* quarter

---

# 🔍 Exploratory Data Analysis

The following analyses were performed:

* Missing value analysis
* Duplicate record detection
* Summary statistics
* Distribution analysis
* Correlation analysis
* Customer segmentation
* Product performance
* Market performance
* Seasonal trend analysis
* Outlier detection using Z-score and IQR

---

# ⚙ Feature Engineering

Created several predictive features including:

* Year
* Month
* Quarter
* Week
* Day of Week
* Lag Features
* Rolling Mean
* Sales Growth
* Profit Percentage
* Region-wise Aggregation
* Product-wise Aggregation

---

Pipeline

```text
Historical Sales
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Sales Forecast
        │
        ▼
Power BI Dashboard
```

---


---
---

# 📊 Power BI Dashboard

The dashboard provides:

* Executive KPI Dashboard
* Revenue Analysis
* Customer Analysis
* Product Analysis
* Regional Performance
* Sales Trend Analysis
* Forecast Dashboard
* Dynamic Filters
* Drill-down Reports

---

# 📸 Dashboard Screenshots

## Executive Dashboard

<img width="1031" height="651" alt="image" src="https://github.com/user-attachments/assets/b83dad52-0530-456a-83a0-0303cf2a70aa" />


---

## Revenue Analysis

<img width="1031" height="657" alt="image" src="https://github.com/user-attachments/assets/377ee8c5-cef3-4553-b9df-c0a1b358cac2" />


---

---

## Forecast Dashboard

<img width="415" height="271" alt="image" src="https://github.com/user-attachments/assets/146d92a6-b087-4f45-8a17-fd96a5b33ad5" />


---

# 📈 Key Business Insights

* Identified top-performing products.
* Detected high-revenue customer segments.
* Analyzed regional sales performance.
* Identified seasonal demand patterns.
* Improved forecasting accuracy using Machine Learning.
* Enabled interactive business reporting.

---

# 🌍 Real-World Applications

* Inventory Management
* Sales Forecasting
* Revenue Planning
* Business Intelligence
* Customer Segmentation
* Market Expansion
* Strategic Planning

---

# 🚀 Future Enhancements

* Deep Learning (LSTM)
* XGBoost Forecasting
* Real-Time Data Streaming
* Azure Deployment
* AWS Deployment
* Docker Support
* CI/CD Pipeline
* Automated Power BI Refresh
* REST API Integration

---

# ▶ Installation

```bash
git clone https://github.com/yourusername/project.git

cd project

pip install -r requirements.txt

python src/forecasting.py
```

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
scikit-learn
statsmodels
sqlalchemy
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Sanjeev A**



---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
