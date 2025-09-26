# sql-datawarehouse-project
Welcome to SQL Datawarehose Project 
Building a modern data warehouse  with SQL Server , including ETL processes ,data modelling and analytics
🏗️ SQL-Based Data Warehouse (Medallion Architecture)
This project implements a full-scale Data Warehouse using the Medallion Architecture (Bronze, Silver, and Gold layers), built entirely with SQL — no external frameworks or tools.
🧱 Architecture Overview

🔹 Bronze Layer: Raw data ingestion from source systems (CSV files, mock APIs, etc.)

🔸 Silver Layer: Cleaned and transformed data using SQL — deduplication, type casting, joins, and enrichment

🟡 Gold Layer: Curated, business-ready datasets optimized for analytics, dashboards, and KPI reporting

🛠️ Technologies Used

SQL (PostgreSQL / MySQL / BigQuery / etc.)

DDL/DML scripts for all layers

Sample source datasets (CSV or SQL inserts)

🚀 Key Features

✅ Clean, modular SQL for data transformation across all layers

✅ Follows best practices in data modeling and pipeline design

✅ Easily extendable and portable to real-world data environments

✅ Simple structure — great for learning or real-world use

📊 Use Cases

Building a data platform from scratch with just SQL

Practicing data modeling (star schema, normalization)

Learning Medallion Architecture in a lightweight way

Demo for data engineering or analytics interviews

📁 Repository Structure
├── bronze/
│   └── raw_data.sql / raw_data.csv
├── silver/
│   └── transformations.sql
├── gold/
│   └── curated_models.sql
├── diagrams/
│   └── medallion_architecture.png (optional)
└── README.md

📌 How to Run

Load the Bronze layer data into your database

Execute SQL scripts in the Silver layer to clean and transform

Run Gold layer scripts to generate final analytical tables

📢 About the Author

I built this project to demonstrate that powerful data architecture doesn't require complex tooling — just a clear understanding of data flow and strong SQL fundamentals.

Feel free to fork, explore, and connect!

🔗https://www.linkedin.com/in/saranya-nandavaram-3ab460282/



🔗 [LinkedIn Profile]

📬 [Portfolio or contact]
