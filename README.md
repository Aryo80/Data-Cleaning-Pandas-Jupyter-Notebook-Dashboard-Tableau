# Nashville Housing Data Cleaning and Visualization
This repository contains a dataset revolving around housing sales in Nashville, Tennessee. The dataset includes crucial information such as sale price, sale date, land use, and property details. This README.md file outlines the process of cleaning and preparing the data for analysis.

## Data Cleaning Process
### Renaming Columns and Data Type Conversion
Renamed columns for consistency and clarity.
Converted specific columns to numerical types and ensured sale_date is in datetime format.
### Handling Missing Values
Removed entries with missing unique_id, as it serves as the primary key.
Removed entries with missing values in land_value, building_value, city, and sale_price columns.
## Data Cleaning and Standardization
Standardized categories in the land_use column by replacing duplicates, typos, and abbreviations.
Corrected entries in the sold_as_vacant column by replacing 'Y' with 'Yes' and 'N' with 'No'.
### Data Analysis and Processing
Calculated profit for each sale by deducing land value and building value from the sale price.
Extracted the year from the sale date to analyze profit growth over the years.
## Data Analysis Results
The analysis provides insights into the business condition in terms of profit growth over the last few years. The results are summarized in the profit_by_year DataFrame.
## Dashboard on Tableau
Explore the insights from the cleaned Nashville housing dataset through an interactive dashboard created on Tableau. The dashboard offers visualizations and filters to dive deeper into the housing sales data, providing a user-friendly interface for analysis.

### Dashboard Features:

Visualizations highlighting key trends in housing sales, profit growth, and land use distribution.
Interactive filters for refining data by sale date, property type, and geographic location.
Comparative analysis of sales performance over time and across different land use categories.
### Access the Dashboard:
Link to Tableau Dashboard - ([ Nashville Housing](https://public.tableau.com/app/profile/mahmood.honarvar/viz/Nashville_17138825706950/Dashboard1?publish=yes))
### File Structure
Nashville.csv: Original dataset.
Cleaned_Nashville.csv: Cleaned dataset after data preparation.
README.md: Detailed information about the data cleaning process and analysis.
### Instructions for Use
Clone or download the repository to your local machine.
Open the cleaned dataset Cleaned_Nashville.csv for further analysis or visualization.
Use the provided Python script for reference or further data processing.
### Dependencies
pandas: For data manipulation and analysis.
