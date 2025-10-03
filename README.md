# Data Warehouse Project 

This portfolio project creates a data warehouse using SQL Server Management Studio 21. 
The project uses the so called Medallion Architecture with Bronze, Silver and Gold layers.

1. Bronze layer: Stores the raw data from the different data sources avaliable as CSV files into an SQL data server.
2. Silver layer: This layer includes data cleansing, standardization and normalization to prepare the data for analysis.
3. Gold layer: Creates business ready data into star schemas that is required for analytics.

Skills used in the project
- ETL / ELT processing
- SQL Development
- Data Architect
- Data Engineering
- ETL Pipeline Developer
- Data Modeling
- Data Analytics

What is a data warehouse?
- It is a digital storing system used to extract, transform and load data from several different sources. The data can be used by the company to make business decisions.

# Summary
- Three folders (bronze, silver, gold) and one file to initialize a database.
- Bronze layer includes two scripts (ddl and proc load). Ddl creates schemas and proc load inserts data into schemas from external csv files. No data cleaning is done here.
- The data source files includes CRM and ERP data.
- Silver layer includes two scripts (ddl and proc load). Ddl creates schmes that fits the data structure for cleaned data. Proc load truncates, transforms and cleanes the bronze layer data and inserts it into silver schemas.
- Gold layer includes one script (ddl). Ddl creates view tables from the silver layer to produce cleaned, enriched and business ready datasets.

# Credit
- Data with Baraa on Youtube
