# CommercePulse Analytics Dashboard

## Overview

CommercePulse is an end-to-end e-commerce analytics project built using Python, Databricks, PySpark, and Spark SQL. The project processes transactional e-commerce data, performs analytical transformations, and generates actionable business insights through advanced SQL techniques and interactive dashboards.

The objective of this project is to simulate a real-world analytics workflow used by data analysts and analytics engineers to monitor business performance, customer behavior, product trends, and retention metrics.

---

## Tech Stack

### Languages

* Python
* SQL

### Tools & Platforms

* Databricks
* PySpark
* Spark SQL
* Google Colab
* GitHub

### Libraries

* Pandas
* NumPy
* Faker
* Matplotlib

---

## Project Architecture

```text
Raw E-Commerce Data
          │
          ▼
Data Cleaning & Validation (Python/Pandas)
          │
          ▼
Cleaned Datasets
          │
          ▼
Databricks Tables
          │
          ▼
Spark SQL Analytics
          │
          ▼
Interactive Dashboard
          │
          ▼
Business Insights
```

---

## Dataset

The project consists of four core datasets:

### Customers

Contains customer profile information.

| Column      |
| ----------- |
| customer_id |
| name        |
| email       |
| signup_date |
| city        |

### Products

| Column       |
| ------------ |
| product_id   |
| product_name |
| category     |
| price        |
| cost         |

### Orders

| Column      |
| ----------- |
| order_id    |
| customer_id |
| order_date  |
| status      |

### Order Items

| Column        |
| ------------- |
| order_item_id |
| order_id      |
| product_id    |
| quantity      |
| unit_price    |

---

## Data Quality & Validation

The dataset was intentionally generated with inconsistencies to simulate real-world challenges.

### Validation Performed

* Duplicate customer detection
* Missing value handling
* Email validation
* Future date validation
* Negative price validation
* Data type standardization
* Referential integrity checks

---

## SQL Analytics Implemented

### Revenue Analysis

* Monthly Revenue Trends
* Revenue by Product Category
* Average Order Value (AOV)

### Customer Analytics

* Customer Lifetime Value (CLV)
* Top Customers
* Customer Segmentation

### Product Analytics

* Top Performing Products
* Category Revenue Analysis

### Advanced SQL Concepts

* Joins
* Aggregations
* Common Table Expressions (CTEs)
* Window Functions
* Ranking Functions
* Running Totals

### Retention Analytics

* Cohort Analysis
* Customer Retention Metrics
* Repeat Customer Analysis

---

## Dashboard Components

### KPI Cards

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value

### Revenue Analytics

* Monthly Revenue Trend
* Revenue by Category

### Customer Analytics

* Customer Segmentation
* Top Customers

### Product Analytics

* Top Products
* Order Status Distribution

### Retention Analytics

* Retention Rate
* Cohort Analysis Heatmap

---


This project was developed to demonstrate practical analytics engineering skills using modern data platforms and industry-standard analytical techniques.
