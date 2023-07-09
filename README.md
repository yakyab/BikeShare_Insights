# BikeShare Insights: Data Analysis of Washington D.C. Bike Sharing System
## Project Description
This project aims to analyze the data from the Bike Sharing system in Washington D.C., specifically focusing on the hourly usage patterns and weather conditions. The analysis will provide insights into usage trends, peak hours, seasonality effects, and the influence of weather conditions on bike rentals.

## Business Problem
With an increasing emphasis on sustainable transportation, bike sharing systems have become common in many cities. Understanding the usage patterns of these systems can help in better management, improve user satisfaction, and optimize resource allocation.

The goal of this project is to address the following business questions:

What are the peak hours and off-peak hours for bike rentals?
How do weather conditions affect bike rentals?
Are there any noticeable differences in the patterns of bike rentals between weekdays and weekends or between different seasons?

## Project Structure
The project is organized in the following structure:

1. Data_Preparation.ipynb: This notebook contains the data acquisition and preprocessing steps. It involves data cleaning, data type conversion, and the removal of unnecessary columns and missing values. The cleaned data is then stored in a SQL database.

2. Data_Analysis.ipynb: This notebook contains the data analysis part where SQL queries are written and executed to extract meaningful insights from the data. 

3. Data_Visualization.ipynb: This notebook prepares the data for visualization and suggests potential visualization types for PowerBI. The processed data is stored in a form that can be easily imported into PowerBI for further visualization.

4. `BikeShare Insights - Report.pdf` - This file contains the final report of the analysis. It is a PDF export of the PowerBI dashboard and includes visualizations of the key insights derived from the data. It provides a concise overview of the bike rentals patterns related to hours, weather conditions, weekdays, and seasons.

The results of the analysis and the data visualizations are saved and organized in a GitHub repository.

## Technology Stack
- Python: Used for data acquisition, cleaning, and analysis. Python's various libraries such as pandas, numpy, and sqlalchemy are used extensively.

- SQL: Used for storing, managing, and querying the cleaned data.

- PowerBI: Used for creating interactive visualizations and dashboards based on the analyzed data.
