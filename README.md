**Planes Feature Engineering #3 - Total Air Time Times**

**Overview**

This repository contains a Jupyter Notebook that performs feature engineering on plane data from a SQL Server database, specifically focusing on calculating the total air time for flight routes. The notebook demonstrates various data manipulation, analysis, and visualization techniques to extract meaningful insights and prepare the data for machine learning models.

**Repository Contents**

Planes - Feature Engineering #3 - Total Air Time Times.ipynb: The main Jupyter Notebook file containing the feature engineering process.

**Key Features**

**SQL Integration:** 
* Connects to a SQL Server database and retrieves data from the flights_cleaned table.
  
**Data Exploration:**
* Provides an overview of the data and unique flight routes.

**Feature Engineering:**
*Calculates distances between locations using the Haversine formula based on latitude and longitude.
*Applies a speed ratio to estimate total air time.
*Deconstructs flight routes and calculates total air time for each route segment.
*Calculates layover times by subtracting total air time from the total duration.

**Data Export:** 
* Saves the cleaned and engineered dataset back to the SQL Server database.

**Data Sources:**
* planes.xlsx: Dataset containing flight information.
* ind_loc.csv: Dataset containing latitude and longitude information.
* indian_city_names.csv: Dataset containing city names.

**Prerequisites:**
* Python 3.x
* Jupyter Notebook
* SQL Server

**Necessary Python libraries: **
pandas, numpy, matplotlib, seaborn, sqlite3
