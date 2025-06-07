# Data-Warehouse-Project
Building a Data warehouse using the medallion architecture, this project includes ETL processes and modeling.

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](https://github.com/user-attachments/assets/2b952fea-3dfb-4ade-8c93-71969ac45acd)

1. **Bronze Layer**: Stores raw data from the source systems. Data is ingested from CSV Files into SQL Server.
2. **Silver Layer**: Includes data transformation (cleansing, standardization, mathematical operations or string manipulations to existing columns).
3. **Gold Layer**: Includes business-ready data modeled into a star schema ready for reporting and analytics.

## 📖 Project Overview

This project includes:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the Data warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.

## 🚀 Project Requirements

### Building the Data Warehouse 
#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

