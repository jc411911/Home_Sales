# Home_Sales
 Module 22 Joe Almendarez

This repository contains a Jupyter Notebook for analyzing home sales data using PySpark. The notebook performs various data processing and analysis tasks on a dataset of home sales.

## Files

- `Home_Sales.ipynb`: The main Jupyter Notebook containing the analysis code.
- `.gitattributes`: Configuration file for Git version control.
- `README.md`: This file.

## Analysis Tasks

The notebook performs the following tasks:

1. Reads home sales data from an AWS S3 bucket into a PySpark DataFrame.
2. Creates temporary views of the data for SQL queries.
3. Calculates various statistics, such as:
   - Average price for a four-bedroom house sold per year.
   - Average price of a home for each year it was built, with specific criteria.
   - Average price of a home per "view" rating.
4. Caches and uncaches data to compare query runtimes.
5. Partitions and reads data in Parquet format.

## Author

Module 22 Joe Almendarez