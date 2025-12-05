🌾 Agriculture Climate Analytics Pipeline (AWS + Snowflake + Power BI)

End-to-end analytics pipeline integrating AWS cloud storage, Snowflake data warehousing, SQL transformations, and Power BI dashboards to analyze climate factors affecting agricultural productivity.

📌 Project Overview

This project delivers a complete data analytics solution for understanding climate impact on agriculture.
It analyzes:

Humidity

Rainfall

Temperature

Crop Yields

across multiple years, seasons, crops, and locations.

The pipeline is built using:
AWS S3 → Snowflake → SQL Transformations → Power BI Visual Analytics.

This demonstrates strong capability in ETL, data modeling, cloud analytics, and BI reporting, similar to enterprise-grade systems.

🏗 Architecture
CSV Raw Data → AWS S3 → Snowflake Stage → Snowflake Warehouse
                     ↓             ↓
                SQL Transformations → Fact/Dim Tables → Power BI Dashboards

⚙️ Technologies Used

AWS S3 (Raw Data Storage)

Snowflake (Data Warehouse)

SQL (Snowflake SQL)

Power BI Desktop

DAX Measures



📊 Power BI Dashboard Overview
✔ Humidity Analysis

Tracks avg. humidity trends across year, season, crop, and region.

✔ Rainfall Analysis

Shows rainfall distribution, crop-wise needs, and region-specific rainfall.

✔ Temperature Analysis

Identifies temperature impact on crops, seasonal variation, and location distribution.

✔ Yield Analysis

Examines productivity patterns, top-yielding crops, and regional outputs.

All dashboard screenshots are stored in POWER_BI_DASHBOARDS/.

🧠 Key Insights

Humidity levels remain stable around 55–56% across most crops and regions.

High-rainfall crops like Paddy require ~3.5K mm annual rainfall.

Seasonal temperature variation strongly influences crop cycle outputs.

Cotton and Coconut emerge as highest-yielding crops in the dataset.

🚀 How to Run This Project

Clone the repository

Upload raw CSV files to AWS S3

Run stage_load.sql and transformations.sql inside Snowflake

Connect Power BI to Snowflake

Open the .pbix file

Refresh the dataset

Dashboards will automatically populate with transformed data
