
# Healthcare Data Engineering Pipeline

An end-to-end synthetic healthcare data engineering project built using Azure Databricks, PySpark, Delta Lake and SQL.

## 1. Project Overview

This project demonstrates an end-to-end healthcare data pipeline using the Medallion Architecture (Bronze, Silver and Gold).

The objective is to demonstrate data ingestion, transformation, data quality validation, incremental processing and analytical reporting using modern data engineering technologies.

**Important:** This is an educational project using synthetic/sample data. It is not a clinically validated system and contains no real patient records.

## 2. Technology Stack

- Azure Databricks
- Apache Spark
- PySpark
- SQL
- Delta Lake
- Medallion Architecture

## 3. Architecture

Source Data → Bronze → Silver → Gold → Analytics

- Bronze: Raw data ingestion.
- Silver: Data cleaning, standardisation and transformation.
- Gold: Analytical tables and healthcare KPI outputs.

Additional components include SQL data quality checks, incremental loading and pipeline verification.

## 4. Project Notebooks

| Notebook | Purpose |
|---|---|
| 01_Bronze_Ingestion_GitHub | Ingest source datasets |
| 02_Healthcare_Silver_Transformation | Clean and transform records |
| 03_Healthcare_End_to_End_Pipeline | Pipeline workflow |
| 04_Healthcare_Gold_Analytics | Analytical outputs |
| 05_Healthcare_SQL_Data_Quality | SQL validation |
| 06_Healthcare_Incremental_Loading | Incremental processing |
| 07_Healthcare_End_to_End_Pipeline | End-to-end verification |

Check the notebooks directory for the exact filenames and execution order.

## 5. Medallion Architecture

### Bronze Layer
Ingests healthcare-style source data and stores raw records.

### Silver Layer
Applies cleaning, standardisation and transformation logic.

### Gold Layer
Creates analytical outputs and healthcare KPI summaries.

## 6. Data Quality

The project explores:
- Null-value validation
- Duplicate detection
- Data consistency
- SQL-based validation
- Incremental processing checks

## 7. Recorded Sample Execution Results

One end-to-end notebook contains the following recorded results:

| Table group | Records |
|---|---:|
| Bronze patients | 10 |
| Bronze doctors | 5 |
| Bronze admissions | 5 |
| Silver hospital records | 5 |
| Gold hospital KPI output | 1 |
| Pipeline audit log | 1 |

These are sample notebook results, not production-scale performance measurements.

## 8. Future Enhancements

- Reusable data quality functions
- Explicit quarantine rejection reasons
- Structured exception handling
- Pipeline run IDs and audit tracking
- Automated repeat-run and idempotency testing
- Improved workspace setup documentation

## 9. How to Explore

1. Open the notebooks directory.
2. Review the notebooks in sequence.
3. Configure your own Databricks compute, catalog and schema.
4. Set up the required data sources and permissions.
5. Execute and verify the pipeline.

## 10. Author

Ramya

GitHub: https://github.com/kvmramya

Repository: https://github.com/kvmramya/healthcare-data-engineering-pipeline

**Project focus:** Healthcare Data Engineering | PySpark | Databricks | Delta Lake | SQL
