# Data Warehouse and Analytics Project

Welcome to my **Data Warehouse and Analytics Project** 🚀
This project demonstrates how to design and implement a complete data warehousing and analytics solution — from raw data ingestion to business-ready insights.

It’s designed as a **portfolio project** to showcase my skills in **Data Engineering, SQL Development, ETL Pipelines, and Analytics** using industry best practices.

---

## 🏗️ Data Architecture

I followed the **Medallion Architecture** approach with **Bronze, Silver, and Gold layers**:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**

   * Stores raw data directly from source systems.
   * Data ingested from CSV files into **SQL Server**.

2. **Silver Layer**

   * Handles data cleaning, deduplication, standardization, and normalization.
   * Prepares data for downstream analytical workloads.

3. **Gold Layer**

   * Business-ready data modeled in a **Star Schema**.
   * Optimized for reporting, dashboards, and advanced analytics.

---

## 📖 Project Overview

The project includes:

* **Data Architecture** → Modern warehouse design (Bronze → Silver → Gold).
* **ETL Pipelines** → Scripts to extract, transform, and load data from ERP & CRM CSV sources.
* **Data Modeling** → Creation of **fact** and **dimension** tables for analytics.
* **Analytics & Reporting** → SQL queries to analyze **Customer Behavior, Product Performance, and Sales Trends**.

🎯 This project highlights my skills in:

* SQL Development
* Data Modeling
* ETL & Data Pipelines
* Data Warehousing
* Analytics & Reporting

---

## 🛠️ Tools & Technologies

* **SQL Server Express** → Database & Data Warehouse
* **SQL Server Management Studio (SSMS)** → Database management
* **CSV Datasets** → ERP and CRM data
* **DrawIO** → Data models, flow, and architecture diagrams
* **Git & GitHub** → Version control and documentation

---

## 🚀 Project Requirements

### Data Engineering – Building the Warehouse

* Consolidate ERP & CRM datasets into SQL Server.
* Ensure **data quality** with cleansing and transformations.
* Integrate into a unified **star schema** for analysis.

### Data Analysis – Reporting & Insights

Developed SQL reports and dashboards with insights into:

* **Customer Behavior** (acquisition, retention, segmentation)
* **Product Performance** (top-selling products, underperformers)
* **Sales Trends** (monthly, quarterly, yearly KPIs)

More details in [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets (ERP & CRM CSV files)
│
├── docs/                               # Documentation & diagrams
│   ├── etl.drawio                      # ETL pipeline design
│   ├── data_architecture.drawio        # Architecture diagram
│   ├── data_catalog.md                 # Dataset catalog & metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema model
│   ├── naming-conventions.md           # Naming standards
│
├── scripts/                            # SQL scripts
│   ├── bronze/                         # Raw data ingestion
│   ├── silver/                         # Data cleansing & transformations
│   ├── gold/                           # Star schema & analytics-ready models
│
├── tests/                              # Quality checks & test scripts
│
├── README.md                           # Project overview
├── LICENSE                             # License
├── .gitignore                          # Git ignored files
└── requirements.txt                    # Dependencies
```

---


## 📬 Connect with Me

If you’d like to collaborate, discuss data, or just connect:

[![LinkedIn](https://www.linkedin.com/in/saishrita-mohapatra-10a943272/)

