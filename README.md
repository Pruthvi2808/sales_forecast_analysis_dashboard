# 📈 Sales Forecasting Dashboard

## 📌 Project Overview

The Sales Forecasting Dashboard is an interactive Business Intelligence and Time Series Analysis solution built using **Power BI, 
Python (ARIMA), Power Query, and DAX**. The project analyzes **1,000 days of daily sales data** across **3 retail stores** to evaluate 
sales trends, store performance, promotional and holiday impact, weekday patterns, and future revenue through a **30-day ARIMA sales forecast**.

---

# 🎯 Problem Statement

Retail businesses often experience fluctuations in daily sales, making inventory planning, promotional decisions, and revenue forecasting challenging. 
Relying on historical trends alone may result in stock shortages, excess inventory, and ineffective promotional planning.

This dashboard provides an interactive platform to analyze:

* Sales Trends Over Time
* Store-wise Sales Performance
* Promotion Impact on Sales
* Holiday Impact on Sales
* Weekday Sales Patterns
* Historical Sales Performance
* 30-Day Forward Sales Forecast using ARIMA

---

# 📂 Dataset Information

| Attribute        | Details                                            |
| ---------------- | -------------------------------------------------- |
| Dataset          | ABC Retail Daily Sales Data                        |
| Records          | **1,000**                                          |
| Stores           | **3**                                              |
| Time Period      | **1 Jan 2020 – 26 Sep 2022**                       |
| Key Variables    | Daily Sales, Store ID, Promotion, Holiday, Weekday |
| Forecast Records | **30**                                             |
| Forecast Period  | **10 Dec 2022 – 8 Jan 2023**                       |
| File Type        | CSV                                                |

---

# 🛠 Technologies Used

* Power BI Desktop
* Python
* ARIMA
* Power Query
* DAX

---

# 🔄 Project Workflow

### Step 1

Imported **1,000 days of daily retail sales data** containing sales revenue, store information, promotional activity, holiday indicators, and weekday information.

### Step 2

Performed **Exploratory Data Analysis (EDA)** using Python to identify missing values, outliers, inconsistencies, sales fluctuations, trends, and recurring patterns.

### Step 3

Analyzed historical sales performance across different stores and evaluated daily, weekly, monthly, promotional, holiday, and weekday sales patterns.

### Step 4

Developed an **ARIMA time series forecasting model in Python** using historical sales data to generate a **30-day forward sales forecast**.

### Step 5

Stored the generated forecast results in the `forecast_results` dataset and prepared the historical and forecast data for Power BI integration.

### Step 6

Imported the datasets into **Power BI Desktop** and used **Power Query** for data transformation, data type validation, and data preparation.

### Step 7

Created data models and **DAX measures** including Total Sales, Average Sales, Promotion Sales, and Number of Stores to support interactive dashboard analysis.

### Step 8

Developed an interactive **Power BI dashboard** with KPI cards, sales trends, store comparisons, promotion and holiday analysis, and a 30-day ARIMA forecast.

### Step 9

Published the completed report to **Power BI Service** for interactive stakeholder reporting and business analysis.

---

# 📈 Dashboard Pages

## 📄 Page 1 – Sales Forecast Overview

Dashboard includes:

* Total Sales KPI
* Average Daily Sales KPI
* Number of Stores KPI
* Promotion Sales KPI
* Historical Sales Trend
* 30-Day ARIMA Sales Forecast

---

## 📄 Page 2 – Store Performance Analysis

Dashboard includes:

* Store-wise Sales Comparison
* Total Sales by Store
* Average Sales by Store
* Store Performance Trends
* Historical Store Performance

---

## 📄 Page 3 – Promotion & Holiday Analysis

Dashboard includes:

* Promotion vs Non-Promotion Sales
* Holiday vs Non-Holiday Sales
* Promotion Impact on Average Sales
* Holiday Impact on Average Sales
* Promotional Day Analysis

---

## 📄 Page 4 – Sales Pattern Analysis

Dashboard includes:

* Weekday Sales Performance
* Daily Sales Trends
* Monthly Sales Patterns
* Sales Fluctuation Analysis
* Historical Growth Trends

---

## 📄 Page 5 – Forecast Analysis

Dashboard includes:

* 30-Day ARIMA Forecast
* Forecasted Daily Sales
* Forecast Average
* Minimum Forecast Value
* Maximum Forecast Value
* Historical vs Forecast Trend

---

# 📊 Dashboard Metrics

The dashboard provides interactive analysis of:

* Total Sales
* Average Daily Sales
* Number of Stores
* Promotion Sales
* Promotional Days
* Holiday Days
* Highest Single-Day Sales
* Lowest Single-Day Sales
* Store-wise Sales
* Weekday Sales
* 30-Day Forecast Average
* Forecast Range

---

# 📉 Key Insights

* **Store 2** recorded the highest total sales at **$104,461.54**, followed by Store 1 at **$102,250.73** and Store 3 at **$93,923.69**.
* **Holiday periods** generated average sales of **$307.41**, compared with **$299.99** during non-holiday periods, representing a **2.47% increase**.
* **Promotional days** recorded average sales of **$301.82**, compared with **$300.11** on non-promotional days, indicating a relatively small **0.57% increase**.
* **Tuesday** was the strongest weekday with average sales of **$303.16**, while **Friday** recorded the lowest average at **$296.40**.
* Average daily sales increased from **$174.10 in 2020** to **$319.82 in 2021** and **$446.77 in 2022**, indicating a strong upward sales trend.
* The **ARIMA model** forecasted average daily sales of **$457.46** over the 30-day forecast period, with predicted values ranging from **$442.44 to $482.18**.

---

# ✨ Features

* 30-Day ARIMA Sales Forecast
* Interactive KPI Cards
* Store-wise Sales Comparison
* Promotion Impact Analysis
* Holiday Impact Analysis
* Weekday Sales Analysis
* Historical Sales Trend Analysis
* Dynamic DAX Measures
* Power Query Data Transformation
* Interactive Power BI Visualizations
* Power BI Service Publishing

---

# 📚 Skills Demonstrated

* Exploratory Data Analysis
* Time Series Analysis
* ARIMA Forecasting
* Python
* Power Query
* Data Cleaning & Transformation
* Data Modeling
* DAX
* Power BI Dashboard Development
* Data Visualization
* Sales Analytics
* Business & Revenue Analysis

---

# 📌 Conclusion

This project demonstrates an end-to-end **Data Analytics and Business Intelligence workflow** by analyzing **1,000 daily retail sales records** across 3 stores using **Python, ARIMA, Power Query, DAX, and Power BI**. It showcases data exploration, transformation, time series forecasting, data modeling, and interactive dashboard development to identify sales trends, store performance, promotional and holiday effects, and future revenue patterns.

With historical sales of **$300,635.96** and a **30-day ARIMA forecast averaging $457.46 per day**, the dashboard demonstrates how historical sales data and predictive analytics can support **inventory planning, promotional strategies, revenue forecasting, and data-driven business decision-making**.
