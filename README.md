# SQL Data Analytics Project Overview

This project is a **continuation** of [SQL DataWareHouse Project](https://github.com/karthimahi/sql-data-warehouse-project/), where we built a modern data warehouse with three layers, bronze, silver and gold **(Medallion Architecture)** to generate actionable insights for decision making.

A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more.

This repository contains SQL queries designed to help data analysts and BI professionals quickly explore, segment, and analyze data within a relational database. Each script focuses on a specific analytical theme and demonstrates best practices for SQL queries.

```
sql-data-analytics-project/
├── datasets/                               the data as CSV files
├── docs/                                   No Files in it.
└── scripts/                                the queries for analysis.
    └── 00_init_database.sql                builds the database (DataWarehouseAnalytics) from the CSV files
    └── 01_database_exploration.sql         To explore the structure of the database, including the list of tables and their schemas
    └── 02_dimensions_exploration.sql       To explore the structure of dimension tables
    └── 03_date_range_exploration.sql       To understand the range of historical data & To determine the temporal boundaries of key data points
    └── 04_measures_exploration.sql         To calculate aggregated metrics (e.g., totals, averages) for quick insights
    └── 05_magnitude_analysis.sql           To quantify data and group results by specific dimensions
    └── 06_ranking_analysis.sql             To rank items (e.g., products, customers) based on performance or other metrics
    └── 07_change_over_time_analysis.sql    For time-series analysis and identifying seasonality.
    └── 08_cumulative_analysis.sql          To calculate running totals or moving averages for key metrics
    └── 09_performance_analysis.sql         To measure the performance of products, customers, or regions over time
    └── 10_data_segmentation.sql            To group data into meaningful categories for targeted insights
    └── 11_part_to_whole_analysis.sql       To compare performance or metrics across dimensions or time periods
    └── 12_report_customers.sql             This report consolidates key customer metrics and behaviors
    └── 13_report_products.sql              This report consolidates key product metrics and behaviors
```
---
## 🗺️ What you build

The project has two parts, and the scripts follow them:

- **Exploratory data analysis**, scripts `01` to `06`: you get to know the data, from the tables and dates to the big numbers and the top performers.
- **Advanced analytics**, scripts `07` to `11`: you go deeper with trends, running totals, performance, part-to-whole and segments. Two reports close the project, one for customers and one for products.
---

## ⚙️ Tools & Services Used

- **Datasets** → Access to the project dataset (csv files).
- **SQL Server Express** → Lightweight server for hosting your SQL database.
- **SQL Server Management Studio (SSMS)** → GUI for managing and interacting with databases.
- **GitHub** →  Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.

---

## 🔄 Project Workflow

### 1. Exploratory data analysis

| Name of the Analysis | Scripts |
|:--|:--|
| **Database Exploration** | [01_database_exploration](scripts/01_database_exploration.sql) |
| **Dimensions Exploration** | [02_dimensions_exploration](scripts/02_dimensions_exploration.sql) |
| **Data Range Exploration** |  [03_date_range_exploration](scripts/03_date_range_exploration.sql) |
| **Measures Exploration** | [04_measures_exploration](scripts/04_measures_exploration.sql) |
| **Magnitude Analysis** | [05_magnitude_analysis](scripts/05_magnitude_analysis.sql) |
| **Ranking Analysis** | [06_ranking_analysis](scripts/06_ranking_analysis.sql) |

### 2. Advanced analytics

| Name of the Analysis | Scripts |
|:--|:--|
| **Change Over Time Analysis** | [07_change_over_time_analysis](scripts/07_change_over_time_analysis.sql) |
| **Cumulative Analysis** | [08_cumulative_analysis](scripts/08_cumulative_analysis.sql) |
| **Performance Analysis** |  [09_performance_analysis](scripts/09_performance_analysis.sql) |
| **Data Segmentation** | [10_data_segmentation](scripts/10_data_segmentation.sql) |
| **Part to Whole Analysis** | [11_part_to_whole_analysis](scripts/11_part_to_whole_analysis.sql) |

### 3. Final Report

| Report Name | Scripts |
|:--|:--|
| **Customers Report** | [12_report_customers](scripts/12_report_customers.sql) |
| **Products Report** | [13_report_products](scripts/13_report_products.sql) |

---

### The SQL projects

| Project| Materials |
|:--|:--|
| **Data Warehouse** |[Repository](https://github.com/karthimahi/sql-data-warehouse-project) |
| **Exploratory Data Analysis** | this repository |
| **Advanced Data Analytics** | this repository  | |

---

### 🛡️License

This project is licensed under the [MIT License]. You are free to use, modify, and share this project with proper attribution.

---
### 🌟About Me

Hi there! I'm **Karthick**. Results-driven **Business & Data Analyst** with **4+** years in Amazon Tech Ops, serving as the primary bridge between global business stakeholders and cross-functional engineering teams to drive catalog expansion, competitor intelligence, and data-led strategic initiatives across JP, SG, AU, Far East, and MENA marketplaces.
