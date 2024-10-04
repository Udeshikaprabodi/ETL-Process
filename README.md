# ETL-Process
# E-Commerce ETL Pipeline Project

## Project Overview
This project demonstrates an end-to-end ETL pipeline for e-commerce data using the **UCI Online Retail Dataset**. The pipeline extracts data from an Excel file, transforms the data by cleaning and calculating total order prices, and loads the data into a MySQL database.

## Steps
- **Extract**: Data is read from an Excel file.
- **Transform**: Cleaned and enriched with new calculated fields.
- **Load**: Data is loaded into a MySQL database for analysis.

## Tools Used
- **Python**: For the ETL pipeline.
- **MySQL**: Database for storing the transformed data.
- **Google Data Studio**: For building a dashboard from the transformed data.

## How to Run the ETL Pipeline
1. Install dependencies: `pip install -r requirements.txt`.
2. Modify the MySQL connection parameters in the `etl_pipeline.py` script.
3. Run the ETL pipeline: `python etl_pipeline.py`.

## Dashboard
You can visualize the data using Google Data Studio by connecting it to the MySQL database.
