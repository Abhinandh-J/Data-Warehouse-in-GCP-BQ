# Data-Warehouse-in-GCP-BQ
Data Warehouses In BigQuery - Build and Optimize

Task 1: Create a Partitioned Table
Create a new partitioned table to store the enriched data.
The table is partitioned by date, with a retention policy of 720 days.

Task 2: Add New Columns
Add new columns for population, country area, and mobility data.

Task 3: Add Country Population Data
Create a new table, 'pop_data_2019,' to store country population data.
Update the 'population' column in the main table using data from 'pop_data_2019.'

Task 4: Add Country Area Data
Update the 'country_area' column in the main table using country area data from 'census_bureau_international.country_names_area.'

Task 5: Populate the Mobility Record Data
Update the mobility data columns in the main table using aggregated data from 'covid19_google_mobility.mobility_report.'

Task 6: Query Missing Data
Retrieve records with missing data in the 'population' and 'country_area' columns.
Identify countries with incomplete population or country area information.

Prerequisites:
Access to Google BigQuery.

Required datasets available in your BigQuery project:
bigquery-public-data.covid19_govt_response.oxford_policy_tracker
bigquery-public-data.covid19_ecdc.covid_19_geographic_distribution_worldwide
bigquery-public-data.census_bureau_international.country_names_area
bigquery-public-data.covid19_google_mobility.mobility_report


Execution:
Create Partitioned Table (Task 1)
Execute the provided SQL script to create a partitioned table to store the enriched data.

Add New Columns (Task 2)
Execute the provided SQL script to add new columns to the table.

Add Country Population Data (Task 3)
Execute the SQL script for creating and updating the 'population' column.

Add Country Area Data (Task 4)
Execute the SQL script to update the 'country_area' column.

Populate Mobility Record Data (Task 5)
Execute the SQL script to populate the mobility data.

Query Missing Data (Task 6)
Execute the SQL queries provided to identify and retrieve records with missing data in the 'population' and 'country_area' columns.
