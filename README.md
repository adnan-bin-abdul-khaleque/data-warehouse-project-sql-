# 📊 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics Project** 🚀  
This project showcases an end-to-end data engineering and analytics workflow — from raw data ingestion to delivering actionable business insights. It is designed as a portfolio project to demonstrate industry best practices in **data warehousing, ETL pipelines, and analytics**.

---

## 🏗️ Architecture Overview

This project follows the **Medallion Architecture** pattern with three layers:

### 🥉 Bronze Layer (Raw Data)
- Stores raw data ingested directly from source systems  
- Data imported from **ERP and CRM CSV files** into SQL Server  
- No transformations applied (preserves source fidelity)

### 🥈 Silver Layer (Cleaned & Transformed Data)
- Handles **data cleansing, standardization, and normalization**
- Resolves data quality issues (missing values, duplicates, inconsistencies)
- Prepares structured datasets for downstream analytics

### 🥇 Gold Layer (Business-Ready Data)
- Contains **analytics-ready data models**
- Implements a **Star Schema** (Fact & Dimension tables)
- Optimized for reporting, dashboards, and business intelligence use cases

---

## 📖 Project Overview

This project includes:

- **Data Architecture Design**  
  Building a scalable data warehouse using Medallion Architecture

- **ETL Pipeline Development**  
  Extracting, transforming, and loading data from multiple sources into SQL Server

- **Data Modeling**  
  Designing fact and dimension tables for efficient analytical querying

- **Analytics & Reporting**  
  Writing SQL queries to generate insights and business metrics

---

## 🎯 Key Objectives

### 🔧 Data Engineering
- Consolidate data from **ERP & CRM systems**
- Ensure high **data quality and consistency**
- Build a **centralized analytical data model**
- Focus on the **latest snapshot of data (no historization)**

### 📊 Data Analytics
Deliver insights on:
- Customer Behavior
- Product Performance
- Sales Trends

---

## 📂 Data Sources

| Source | Description |
|--------|------------|
| ERP    | Sales transactions and product data |
| CRM    | Customer information and interactions |

---

## 🧱 Data Model

- **Fact Table**
  - Sales transactions
- **Dimension Tables**
  - Customers
  - Products
  - Time

Schema follows a **Star Schema design** to optimize query performance.

---

## 📈 Sample Business Insights

- Top-performing products by revenue  
- Customer segmentation and purchasing behavior  
- Monthly and yearly sales trends  
- Revenue contribution by customer groups  

---

## 🛠️ Tech Stack

- **Database:** SQL Server  
- **Data Processing:** SQL (T-SQL)  
- **Data Format:** CSV Files  
- **Architecture:** Medallion (Bronze, Silver, Gold)  

---

## 📌 Project Highlights

- End-to-end **data pipeline implementation**
- Real-world **data cleaning and transformation**
- Scalable **data warehouse design**
- Business-focused **analytical queries**
- Clear and structured **data modeling approach**

---

## 📄 Documentation

- Data model documentation included for:
  - Business stakeholders  
  - Data analysts  
- Clear table relationships and schema design explained

---

## 🚀 Getting Started

1. Load CSV files into SQL Server (Bronze Layer)  
2. Run transformation scripts for Silver Layer  
3. Build Gold Layer using star schema  
4. Execute analytical queries for reporting  

---

## 👤 Author

Adnan Bin Abdul Khaleque
