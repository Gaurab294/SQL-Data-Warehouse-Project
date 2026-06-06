# SQL Data Warehouse Project

A portfolio project demonstrating a modern data warehouse lifecycle using SQL Server—from ETL processing and data modeling to final analytics.

## 🏗️ Data Architecture
This project utilizes the industry-standard **Medallion Architecture**, ensuring data is refined and structured for high-performance reporting:

- **Bronze Layer (Raw):** Stores raw source data ingested from CSV files into the SQL environment.
- **Silver Layer (Cleaned):** Processes, cleans, and standardizes data to resolve quality issues.
- **Gold Layer (Business Ready):** Aggregates data into a star schema model optimized for analytical queries.

## 🚀 Project Highlights
- **ETL Pipeline:** Built modular T-SQL scripts to automate the flow of data across architectural layers.
- **Data Quality:** Implemented robust cleaning logic to handle inconsistencies and maintain data integrity.
- **Data Modeling:** Designed normalized dimension and fact tables to support complex business reporting.

## 📊 Project Ecosystem
This repository focuses on the **Engineering** phase of the data lifecycle.

- **Analytics & EDA:** Companion repository focused on exploratory data analysis, KPI reporting, and business insights built on top of this warehouse:
  [SQL Data Analytics Project](https://github.com/Gaurab294/SQL-Data-Analytics-Project)

## 📂 Repository Structure
```text
SQL-Data-Warehouse-Project/
├── Datasets/      # Source ERP and CRM data files
├── scripts/       # Core SQL transformation logic
│   ├── Bronze/    # Scripts for raw data ingestion
│   ├── silver/    # Scripts for data cleaning
│   ├── gold/      # Scripts for analytical star schema models
│   ├── initial_database.sql # Database initialization script
├── tests/         # Quality assurance and validation scripts
└── README.md      # Project overview
