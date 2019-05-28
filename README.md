# Data-Engineering-Topos
Technical programming challenge for the Data Science Engineering Internship position at Topos.

## Requirements
1. Beautiful Soup
2. Pandas - Numpy 
3. Geopandas 
4. JSON
5. Jupyter Notebooks

## Files Included 
### Main Scraping Notebook 
Includes the code used to scrape the wikipedia websites and 
build the table as a pandas dataframe. This pandas dataframe was further
modified to be a geopandas dataframe to allow a geometry column.

### JSON schema
Schema for the table with renamed columns. 
Note: To be used if the automatic schema detection is not available 

### BigQuery Startup Code
Code to port the CSV to bigquery, along with client information and 
dataset ID.

## Credits 
1. Google BigQuery Documentation 
2. Beautiful Soup Documentation 
