# Retail ELT Lab — Python, pandas, SQLite & SQL

## Overview
This repository contains my Retail Data ELT lab assignment. The lab focuses on extracting retail data from CSV files, loading it into SQLite, transforming data using SQL, performing data-quality checks, and conducting business analysis.

## Tools Used
- Python
- pandas
- SQLite
- SQL
- Google Colab

## Dataset
The lab uses four CSV files:
- `customers.csv`
- `products.csv`
- `orders_raw.csv`
- `orders_clean.csv`

## Objectives
- Inspect CSV datasets using pandas
- Load raw data into SQLite
- Understand table schemas and data grain
- Create SQL staging views
- Perform data-quality checks
- Analyze retail data using SQL
- Reconcile raw and clean datasets

## Findings Summary

- Loaded customer, product, raw order, and cleaned order datasets using Python and pandas.
- Stored raw datasets in SQLite and created staging views for analysis.
- Performed data quality checks for missing values, duplicates, invalid records, and referential integrity.
- Conducted retail analysis covering overall sales, product performance, customer performance, and monthly trends.
- Reconciled the raw orders dataset with the cleaned orders reference dataset and documented differences.

## Deliverables

- `Retail_ELT_Riya.ipynb` — Completed ELT workflow, SQL queries, outputs, and analysis.
- `retail_lab.db` — SQLite database containing the raw tables and staging views.

---
**Author:** Riya Yadav
