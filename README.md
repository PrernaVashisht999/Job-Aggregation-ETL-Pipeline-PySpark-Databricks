# Job Aggregation ETL Pipeline using PySpark and Databricks

## Project Overview

Built an end-to-end ETL pipeline in Databricks to ingest and process 100+ job listings from SerpApi using PySpark. The project follows a 3-layer Medallion Architecture to transform raw API data into structured datasets for hiring roles, companies, and location insights.

## Architecture Diagram

The architecture diagram is included in this repository as a `.drawio` file. It shows how raw job data flows through Bronze, Silver, and Gold layers.

## Tech Stack

* Python
* PySpark
* Apache Spark
* Spark SQL
* Databricks
* SerpApi
* Google Jobs API
* Draw.io

## Data Processing Workflow

1. Ingested job listing data from SerpApi
2. Loaded raw API response data into the Bronze layer
3. Converted semi-structured API data into structured format
4. Applied deduplication, null handling, and schema standardization in the Silver layer
5. Created Gold-layer datasets for hiring roles, companies, and location insights.

## Medallion Architecture

### Bronze Layer

* Stored raw job listing data from SerpApi
* Preserved original API response structure for initial ingestion

### Silver Layer

* Cleaned and standardized semi-structured job data
* Applied deduplication and null handling
* Standardized fields such as job title, company, location, and skills

### Gold Layer

* Created structured datasets for reporting-style insights
* Generated outputs for top hiring roles, companies, and locations

## Key Outcomes

* Processed 100+ job listings from SerpApi
* Reduced null and duplicate records by ~10% during Silver-layer cleaning
* Designed a 3-layer Medallion Architecture using Bronze, Silver, and Gold layers
* Converted semi-structured API data into clean, structured datasets

## Skills Demonstrated

* API-based data ingestion
* PySpark transformations
* Spark SQL processing
* Semi-structured data handling
* Data cleaning and validation
* Schema standardization
* Medallion Architecture
* ETL pipeline development
* Databricks workflow execution


 
