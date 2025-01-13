Big Data Analysis Using PySpark
Overview
This project demonstrates the analysis of a large dataset using PySpark, a powerful tool for distributed data processing. The tasks include data preprocessing, schema manipulation, and performing basic analytics on transportation data to extract meaningful insights.

Project Details
Name: Ashika Jain
Company: CODTECH IT SOLUTIONS
ID: CT08FDI
Domain: Data Analytics
Duration: December 2024 to January 2025
Key Tasks Performed
Environment Setup

Installed and initialized PySpark for distributed data processing.
Data Loading

Loaded the dataset containing yellow taxi trip data in CSV format.
Displayed the schema and previewed the data.
Data Cleaning

Dropped rows with missing values to ensure data quality.
Standardized column data types, such as converting pickup and drop-off timestamps.
Exploratory Data Analysis (EDA)

Analyzed hourly trends in taxi trip frequencies.
Computed the average trip distance.
Insights Derived

Identified peak hours for taxi trips.
Gained an understanding of trip distance distributions.
Installation and Requirements
Software
Python 3.8+
Apache Spark (via PySpark)
Dependencies
Install the required library using:

bash
Copy code
pip install pyspark  
How to Run the Notebook
Ensure PySpark is installed and configured in your environment.
Download and place the dataset (e.g., yellow_tripdata_2019-01.csv) in the appropriate directory.
Open the Jupyter Notebook (Big_Data_Analysis.ipynb) and execute the cells sequentially.
Dataset Description
The dataset used in this project contains information about New York City yellow taxi trips, including:

Pickup and drop-off times
Trip distances
Fare amounts
The data was preprocessed to remove inconsistencies and prepare it for analysis.

