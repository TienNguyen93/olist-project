# Brazilian E-Commerce Data Pipeline with Databricks
An end-to-end ETL pipeline built on Databricks to analyze Brazilian e-commerce data, demonstrating production-grade data engineering practices using Medallion architecture, Spark optimization, and AI-powered business intelligence.

## Project Overview
This project processes over 100k e-commerce orders from the Brazilian E-Commerce Public Dataset by Olist on Kaggle. The pipeline ingests raw CSV data, transforms it through multiple quality layers, and generates actionable business insights using Databricks AI/BI tools.

### Key Objectives:

* Build a scalable, production-ready ETL pipeline
* Implement data quality management using Medallion architecture
* Generate business intelligence metrics for executive dashboards
* Leverage AI for feature engineering and sentiment analysis
* Demonstrate hands-on Databricks expertise through self-directed learning

### Architecture
#### Medallion Architecture 

**Bronze Layer (Raw Data Ingestion)**

* Ingests 8 CSV files from the Olist dataset
* Preserves raw data without transformation
* Implements schema validation and data lineage tracking

**Silver Layer (Cleaned & Validated)**

* Data quality checks and validation
* Handles missing values and duplicates
* Standardizes data types and formats
* Joins related tables for enriched datasets

**Gold Layer (Business-Ready Analytics)**

* Aggregated business metrics
* Customer segmentation analysis
* Product performance metrics
* Delivery performance indicators
* 15+ key business intelligence metrics ready for visualization

### Key Results
* ✅ Performance: Reduced data transformation time by 40% through optimized Spark queries
* ✅ Scale: Processed 100K+ orders across 8 interconnected CSV files
* ✅ Business Value: Generated 15+ executive-level business intelligence metrics
* ✅ AI Integration: Automated feature engineering for delivery delay prediction using Genie AI
* ✅ Insights: Performed sentiment analysis on customer reviews to identify improvement opportunities

### Demo
[Dashboards review video](https://youtu.be/Z5CKsHc4Pa0)
