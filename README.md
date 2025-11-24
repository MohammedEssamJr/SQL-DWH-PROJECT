# 📦 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics** project! 🚀\
This repository showcases a complete end-to-end data engineering and
analytics solution --- from ingesting raw data all the way to producing
actionable insights and analytical dashboards.\
It's designed as a portfolio-ready project that demonstrates industry
best practices.

------------------------------------------------------------------------

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** consisting of
Bronze, Silver, and Gold layers:

![Data Architecture](./docs/data_architecture.png)

### **1. Bronze Layer**

-   Stores raw, unprocessed data ingested directly from source systems.\
-   Data is imported from CSV files into SQL Server.

### **2. Silver Layer**

-   Performs data cleaning, standardization, and normalization.\
-   Ensures data quality before it moves into analytical modeling.

### **3. Gold Layer**

-   Contains business-ready, analytics-optimized tables.\
-   Structured using a **Star Schema** for efficient BI reporting.

------------------------------------------------------------------------

## 📖 Project Overview

This project includes:

### **✔️ Data Architecture**

Designing a modern data warehouse using the Medallion approach.

### **✔️ ETL Pipelines**

Extracting, transforming, and loading data into SQL Server through
automated and modular processes.

### **✔️ Data Modeling**

Creating fact and dimension tables optimized for analytical workloads.

### **✔️ Analytics & Reporting**

Building SQL-based insights and BI dashboards that support business
decision-making.

------------------------------------------------------------------------

## 🎯 Skills Demonstrated

This repository is ideal for showcasing expertise in:

-   SQL Development\
-   Data Engineering\
-   ETL / ELT Pipeline Design\
-   Data Modeling\
-   Data Architecture\
-   Analytics & Reporting

------------------------------------------------------------------------

## 🚀 Project Requirements

### **Objective**

Build a modern, well-documented SQL Server data warehouse to consolidate
sales data and support analytics.

### **Specifications**

-   **Data Sources:** Two CSV datasets (ERP & CRM).\
-   **Data Quality:** Clean and standardize inconsistent records before
    analysis.\
-   **Integration:** Merge sources into a unified analytical model.\
-   **Scope:** Focus on latest data; historization not required.\
-   **Documentation:** Deliver clear diagrams and explanations for
    business and technical teams.

------------------------------------------------------------------------

## 📁 Repository Structure

The project structure is organized following clean data engineering best
practices:

    SQL-DWH-PROJECT/
    │
    ├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
    │
    ├── docs/                               # Project documentation and architecture details
    │   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
    │
    ├── scripts/                            # SQL scripts for ETL and transformations
    │   ├── bronze/                         # Scripts for extracting and loading raw data into Bronze layer
    │   ├── silver/                         # Scripts for cleaning, standardizing, and transforming data
    │   ├── gold/                           # Scripts for building analytical models and star schema tables
    │
    ├── tests/                              # Test scripts and data quality validation checks
    │
    ├── README.md                           # Main project documentation and overview
    ├── LICENSE                             # License information (MIT License)

------------------------------------------------------------------------

## 📜 License

This project is licensed under the **MIT License**, granting permission
to use, modify, and distribute the project with proper attribution.

    MIT License

    Copyright (c) 2025 [Mohammed Essam]

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
