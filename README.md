# Energy-Economy Nexus Analysis

A Data Warehouse and ETL project that integrates U.S. electricity market data with global macroeconomic indicators to analyze the relationship between electricity price volatility and economic conditions during the 2022–2024 period.

---

## Project Overview

This project develops an end-to-end data warehouse pipeline using Apache Airflow, PostgreSQL, and Python to automate data extraction, transformation, and loading (ETL).

The integrated warehouse combines multiple public datasets into a unified analytical model that supports multidimensional analysis and business intelligence.

---

## Research Title

**Energy-Economy Nexus: Analyzing the Co-Movement of U.S. Electricity Price Shocks and Global Macroeconomic Indicators During the 2022–2024 Volatility Period**

---

## Objectives

- Build an automated ETL pipeline
- Design a dimensional Data Warehouse
- Integrate multiple public datasets
- Analyze electricity prices and macroeconomic indicators
- Support multidimensional OLAP analysis

---

## Technologies

- Python
- PostgreSQL
- Apache Airflow
- Pandas
- NumPy
- SQLAlchemy
- Jupyter Notebook

---

## Data Sources

### U.S. Energy Information Administration (EIA)

Monthly electricity data including:

- Electricity generation
- Retail electricity prices
- Revenue
- Electricity sales
- Customer counts

Coverage:
January 2022 – December 2024

API:
https://www.eia.gov/opendata/

---

### World Bank Global Economic Monitor

Macroeconomic indicators including:

- GDP
- CPI
- Industrial Production
- Exchange Rate
- Unemployment Rate

Coverage:
January 2022 – December 2024

Source:
https://datacatalog.worldbank.org/

---

## ETL Pipeline

The project automates the following workflow:

Extract

↓

Transform

↓

Load

↓

Data Warehouse

↓

OLAP Analysis

↓

Visualization

---

## Repository Structure

```
energy-economy-nexus-analysis
│
├── README.md
├── requirements.txt
├── energy_etl_dag.py
├── query_by_HESA.ipynb
│
├── data/
│   └── raw_csv/
│
├── reports/
│   ├── Final_Report.pdf
│   ├── Star_Schema.png
│   ├── Dashboard_Overview.png
│   ├── Dashboard_Electricity.png
│   ├── Dashboard_Macroeconomy.png
│   └── Airflow_DAG.png
│
└── notebooks/
```

---

## Data Warehouse Architecture

This project follows the classic ETL architecture:

1. Extract data from EIA API
2. Collect macroeconomic indicators
3. Clean and transform datasets
4. Build Star Schema
5. Load into PostgreSQL
6. Execute OLAP analysis
7. Produce analytical dashboards

---

## Apache Airflow

Apache Airflow orchestrates the complete ETL workflow.

Pipeline Tasks:

- Extract Energy Data
- Extract Macroeconomic Data
- Data Cleaning
- Data Transformation
- Load into PostgreSQL
- Data Validation

---

## Results

The integrated warehouse enables analysis of:

- Electricity price trends
- Energy consumption patterns
- Economic indicator relationships
- Monthly price fluctuations
- Cross-domain analytical insights

---

## Author

**Fio Octriyanti**

Data Science Undergraduate

State University of Surabaya
