# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:  
![Data Architecture](high_level_architecture.png)

1. **🥉 Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server Database.  
2. **🥈 Silver Layer**: Includes data cleansing, standardization, and normalization processes to prepare data for analysis.  
3. **🥇 Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 📖 Project Overview

This project demonstrates a comprehensive **data warehousing and analytics solution** using SQL Server, from building a data warehouse to generating actionable insights.  

This repository is based on a **step-by-step guided project by [Data With Baraa](https://www.youtube.com/@DataWithBaraa)**, with datasets provided in the [tutorial](https://www.youtube.com/watch?v=9GVqKuTVANE&list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7&index=3&t=14838s). It is designed as a portfolio project to showcase industry best practices in data engineering and analytics.

This project involves:

1. 🏗️ **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture (Bronze, Silver, Gold).  
2. 🔄 **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.  
3. 📐 **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.  
4. 📊 **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.  

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:  
- 🧩 SQL Development  
- 🏛️ Data Architecture  
- 🛠️ Data Engineering  
- 🔄 ETL Pipeline Development  
- 📐 Data Modeling  
- 📊 Data Analytics  
---

## 🛠️ Important Links & Tools

Everything is free!  

- 📂 **[Datasets](datasets/):** Access the project dataset (CSV files).  
- 🖥️ **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.  
- 🖱️ **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.  
- 🌐 **[Git Repository](https://github.com/):** Manage, version, and collaborate on your code efficiently.  
- 📊 **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.  
- 🗂️ **[Notion Project Steps](https://www.notion.so/SQL-Data-Warehouse-Project-2f82c3bb04068096bb08fc4e7041ca26?source=copy_link):** Access all project phases and tasks.

---

## 🚀 Project Requirements

### 🏢 Building the Data Warehouse (Data Engineering)

#### 🎯 Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### 📋 Specifications
- 📁 **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.  
- 🧹 **Data Quality**: Cleanse and resolve data quality issues prior to analysis.  
- 🔗 **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.  
- ⏱️ **Scope**: Focus on the latest dataset only; historization of data is not required.  
- 📖 **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### 📊 BI: Analytics & Reporting (Data Analysis)

#### 🎯 Objective
Develop SQL-based analytics to deliver detailed insights into:  
- 👥 **Customer Behavior**  
- 📦 **Product Performance**  
- 💵 **Sales Trends**  

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # 📂 Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # 📝 Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # ✅ Test scripts and quality files
│
├── README.md                           # 📖 Project overview and instructions
├── LICENSE                             # 🛡️ License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi! I'm [Gabriela Yordanova](https://www.linkedin.com/in/gabriela-yordanova-837ba2124/). I have a diverse professional background, with experience in pharmacy and real estate, where I developed strong analytical thinking, attention to detail, and problem-solving skills in fast-paced, customer-focused environments.

I am currently transitioning into a career in data analysis, dedicating my time to learning key tools and techniques, including SQL, data cleaning, data visualization, and data modeling. I am actively applying these skills by working on hands-on projects, building a portfolio that demonstrates my ability to transform raw data into actionable insights.

I am passionate about using data to drive informed decision-making and eager to contribute my analytical mindset and transferable experience to a dynamic, data-driven team.