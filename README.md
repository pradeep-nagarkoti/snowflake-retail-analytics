# snowflake-retail-analytics
An end-to-end data pipeline project built using Snowflake, demonstrating data ingestion, SQL-based ETL transformations, and structured data warehousing for retail analytics.

##  Overview

This project simulates a real-world retail data workflow by building a data pipeline in Snowflake. It covers warehouse setup, data loading from CSV files, and transforming raw data into analysis-ready datasets.

##  Datasets

- **Daily Revenue** -Transaction-level sales data  
- **Product** - Product details and attributes  
- **Region** - Geographic sales data  


##  Architecture

- Created a virtual warehousefor compute  
- Designed database, schema, and tables 
- Loaded CSV data into Snowflake tables  
- Structured data for efficient querying  

##  SQL Scripts

The project is organized into four SQL files:

- **Setup.sql**  
  - Warehouse creation  
  - Database & schema setup  
  - Table creation  

- **Daily_Revenue_Analysis.sql**  
  - Basic to advanced ETL transformations  
  - Revenue analysis queries  

- **Product_Analysis.sql**  
  - Product-level insights and transformations  

- **Region_Analysis.sql**  
  - Region-based analysis and aggregations  

##  ETL Pipeline

- **Ingestion**: Loaded CSV files into Snowflake  
- **Transformation**:
  - Data cleaning and formatting  
  - Joins across datasets  
  - Aggregations and derived metrics  
- **Storage**: Saved processed data into structured tables  


##  Tech Stack

- Snowflake  
- SQL  
- Data warehouse & Data Pipeline 


##  Key Highlights

- Built an end-to-end data pipeline in Snowflake  
- Implemented SQL-based ETL workflows  
- Integrated multiple datasets for analytics  

##  Conclusion

This project demonstrates core data engineering & analytics concepts including data ingestion, transformation, and warehouse design using Snowflake.
