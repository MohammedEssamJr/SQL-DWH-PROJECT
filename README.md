# 📦 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics** project! 🚀  
This repository showcases a complete end-to-end data engineering and analytics solution — from ingesting raw data all the way to producing actionable insights and analytical dashboards.  
It’s designed as a portfolio-ready project that demonstrates industry best practices.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** consisting of Bronze, Silver, and Gold layers:
![Data Architecture](./docs/data_architecture.png)
### **1. Bronze Layer**
- Stores raw, unprocessed data ingested directly from source systems.  
- Data is imported from CSV files into SQL Server.

### **2. Silver Layer**
- Performs data cleaning, standardization, and normalization.  
- Ensures data quality before it moves into analytical modeling.

### **3. Gold Layer**
- Contains business-ready, analytics-optimized tables.  
- Structured using a **Star Schema** for efficient BI reporting.

---

## 📖 Project Overview

This project includes:

### **✔️ Data Architecture**
Designing a modern data warehouse using the Medallion approach.

### **✔️ ETL Pipelines**
Extracting, transforming, and loading data into SQL Server through automated and modular processes.

### **✔️ Data Modeling**
Creating fact and dimension tables optimized for analytical workloads.

### **✔️ Analytics & Reporting**
Building SQL-based insights and BI dashboards that support business decision-making.

---

## 🎯 Skills Demonstrated

This repository is ideal for showcasing expertise in:

- SQL Development  
- Data Engineering  
- ETL / ELT Pipeline Design  
- Data Modeling  
- Data Architecture  
- Analytics & Reporting  

---

## 🚀 Project Requirements

### **Objective**
Build a modern, well-documented SQL Server data warehouse to consolidate sales data and support analytics.

### **Specifications**
- **Data Sources:** Two CSV datasets (ERP & CRM).  
- **Data Quality:** Clean and standardize inconsistent records before analysis.  
- **Integration:** Merge sources into a unified analytical model.  
- **Scope:** Focus on latest data; historization not required.  
- **Documentation:** Deliver clear diagrams and explanations for business and technical teams.

---

