# Learning-Performance-Intelligence-System-LPIS-

For this project, I designed and implemented a full end-to-end Data Warehouse solution for a Digital Learning Analytics platform, using real-world data engineering concepts.

Here's what I built 👇

🗂 Multi-source ETL Pipeline
Extracted data from CSV files, an Excel workbook, and a SQL Server database — simulating a real heterogeneous data environment. Used SSIS (SQL Server Integration Services) to automate the entire ETL process.

⭐ Star Schema Design
Designed a clean star schema with:
• Fact_Learning (central fact table)
• Dim_Learner (with SCD Type 2 for historical tracking)
• Dim_Course, Dim_AppUsage, Dim_Date

📊 Accumulating Fact Table
Extended Fact_Learning to track the full lifecycle of learner activity — from creation time to completion time — and calculated processing duration using conditional SQL logic.

🔄 Slowly Changing Dimensions (SCD Type 2)
Implemented SCD Type 2 on Dim_Learner to preserve historical changes in learner attributes like employment status, country, and education level.

✅ Data Validation
Applied timestamp validation, negative value prevention, referential integrity checks, and data type conversion across all layers.

This project gave me hands-on experience with data modeling, ETL pipelines, dimensional design, and BI architecture — skills I'm excited to keep building on.


#DataWarehouse #BusinessIntelligence #SSIS #ETL #SQLServer #DataEngineering #StarSchema #SLIIT #StudentProject #DataAnalytics
