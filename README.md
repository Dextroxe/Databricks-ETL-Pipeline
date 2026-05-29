# Databricks ETL Pipeline using Medallion Architecture

End-to-end ETL pipeline built on Databricks using PySpark, Delta Lake, and Unity Catalog following the Medallion Architecture (Bronze → Silver → Gold) approach for structured and governed data processing.

---

## Architecture

![Architecture](images/architecture.png)

---

## Tech Stack

* Databricks Community Edition
* PySpark
* Delta Lake
* Unity Catalog
* CSV Data Source
* Medallion Architecture

---

## Project Overview

This project demonstrates a scalable ETL workflow implemented in Databricks using layered data architecture.

The pipeline processes CSV-based datasets through multiple transformation stages:

### Bronze Layer

* Raw data ingestion
* Initial schema handling
* Landing raw datasets into Delta tables

### Silver Layer

* Data cleaning
* Null handling
* Schema standardization
* Deduplication
* Transformation workflows

### Gold Layer

* Analytics-ready curated datasets
* Aggregated and business-friendly data views
* Optimized structured datasets for downstream analysis

---

## Pipeline Workflow

![Pipeline Workflow](images/pipeline.png)

---

## Key Features

* End-to-end ETL pipeline implementation
* Layered Medallion Architecture
* Data quality improvement workflows
* PySpark-based transformations
* Delta Lake storage format
* Structured and governed datasets using Unity Catalog
* Reusable transformation workflows

---

## Data Processing Steps

1. Ingested CSV datasets into Bronze layer
2. Performed schema validation and standardization
3. Cleaned and transformed datasets using PySpark
4. Created curated Silver datasets
5. Generated analytics-ready Gold datasets
6. Published final datasets into Unity Catalog

---

## Concepts Used

* ETL Pipelines
* Data Transformation
* Data Cleaning
* Schema Management
* Delta Lake
* Data Governance
* Layered Data Architecture
* Structured Data Processing

---

## Repository Structure

```bash
.
├── notebooks/
├── datasets/
├── images/
├── README.md
```

---

## Future Improvements

* Add streaming ingestion workflows
* Integrate Databricks Workflows orchestration
* Implement automated data quality checks
* Add dashboarding and analytics layer
* Process larger real-world datasets

---

## Author

Dashmat Hembram

* GitHub: https://github.com/Dextroxe
* LinkedIn: https://linkedin.com/in/dashmat-hembram
