# Data-Engineering-Topos
Technical programming challenge for the Data Science Engineering Internship position at Topos.

## Requirements
1. Beautiful Soup
2. Pandas - Numpy 
3. Geopandas 
4. JSON
5. Jupyter Notebooks

## Files Included 
### Main Scraping Notebook - Data.ipynd
Includes the code used to scrape the wikipedia websites and 
build the table as a pandas dataframe. This pandas dataframe was further
modified to be a geopandas dataframe to allow a geometry column.

### JSON schema - Document.json
Schema for the table with renamed columns. 
Note: To be used if the automatic schema detection is not available 

### BigQuery Startup Code - table_schema.json
Code to port the CSV to bigquery, along with client information and 
dataset ID.

### CSV file with final table - export_dataframe.csv
Final csv file to be uploaded to BQ

## Credits 
1. Google BigQuery Documentation 
2. Beautiful Soup Documentation 
