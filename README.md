# Retail Store Chain Analysis - Assignment

## Overview
This repository contains the solution for **Assignment 3: Retail Store Chain Analysis**, focusing on analyzing retail store sales data from the **Superstore Sales Dataset**.

### Core Requirements

#### Dataset: 
- **Superstore Sales Dataset** (available on [Kaggle: Sales Forecasting](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting))

#### Data Pipeline

- Clean retail data using Python (handling missing values, duplicates).
- Process sales history with PySpark.
- Design efficient PostgreSQL schema for retail analytics.

#### Transformations

- Product hierarchy organization.
- Sales aggregations by region/category.
- Customer purchase patterns.

#### Analysis Features

- Product performance metrics.
- Regional sales comparison.
- Seasonal trend analysis.
- Customer segment profitability.
- Build KPI summary tables.

#### Deliverables:

- **ETL Pipeline Code**: Scripts for extracting, transforming, and loading data.
- **Analysis Queries**: Queries used to analyze the dataset and generate insights.
- **Sales Forecasting Model**: Implementation of forecasting techniques.
- **Project Documentation**: Detailed documentation describing the project, including methodology, results, and findings.

## Project Structure

- `1_data_pipeline/1_pandas_data_cleaning_pipeline.py`: Python script for initial data cleaning.
- `1_clean_data.ipynb`: Data cleaning notebook for preprocessing the dataset.
- `2_process_sales_history.ipynb`: Processes sales history for analysis.
- `3_postgreSQL_schema.sql`: Defines PostgreSQL schema for the database.
- `4_pyspark_to_sql.ipynb`: Loads processed data into PostgreSQL using PySpark.
- `5_sql_analysis_query.sql`: SQL queries for data analysis.
- `6_transformations.ipynb`: Data transformation and aggregation notebook.
- `7_analysis_features.ipynb`: Performs analysis and generates insights.
- `8_dip_analysis.ipynb`: Identifies products with declining sales trends.
- `9_sales_forecast.ipynb`: Implements sales forecasting using machine learning models.

## Folder Structure

  project_root/
├── 1_data_pipeline/

│   ├── 1_clean_data.ipynb

│   ├── 1_pandas_data_cleaning_pipeline.py

│   ├── 2_process_sales_history.ipynb

│   ├── 3_postgreSQL_schema.sql

│   ├── 4_pyspark_to_sql.py

│   ├── 5_sql_analysis_query.sql

├── 2_transformations/

│   ├── 6_transformations.ipynb

├── 3_analysis_features/

│   ├── 7_analysis_features.ipynb

├── 4_modifications/

│   ├── 8_dip_analysis.ipynb

│   ├── 9_sales_forecast.py

├── data/

│   ├── pandas_cleaned_data/

│   ├── 4_final_data.csv

│   ├── train.csv

├── project_documentation/

│   ├── project_documentation.pdf

├── README.md

├── config.yaml  

## Team Members

- **Varsha U**
- **Muneer A**
