# NYC Yellow Taxi Trip Data Analysis

## Project Overview

This project involves analyzing a dataset containing information about NYC yellow taxi cab trips. The primary goal is to implement various data processing and querying tasks using two NoSQL databases: MongoDB and Cassandra. The analysis aims to answer specific questions and provide insights into taxi trip patterns.

## Dataset

The dataset is divided into two CSV files:
- **taxitripdata.csv:** Contains relevant trip data, including pickup and drop-off zones.
- **taxizonegeo.csv:** Contains the longitude and latitude coordinates of the pickup zone areas, represented as polygon vertices.

## Tasks

### Data Preparation
1. **Remove Columns:**
   - Remove the columns `store_and_fwd_flag`, `rate_code`, and `total_amount` from `taxitripdata.csv`.

2. **Drop Incomplete Rows:**
   - Drop rows with missing essential details required for the upcoming queries.

3. **Insert Data:**
   - Insert the cleaned data into MongoDB and Cassandra databases.

### Data Processing
4. **Calculate Trip Duration:**
   - Calculate the duration for each trip and add it as a new field in the database.

5. **Calculate Total Trip Cost:**
   - Use `fare_amount`, `extra`, `mta_tax`, `tip_amount`, `tolls_amount`, and `imp_surcharge` to calculate the total trip cost and add it as a new field in the database.

### Queries and Analysis
6. **Common Payment Type:**
   - Determine the most common payment type used per time of day (morning, afternoon, evening).

7. **Average Tip Amount:**
   - Calculate the average tip amount per passenger count.

8. **Best Pickup Locations:**
   - Identify the best 5 locations for drivers to pick up passengers.

### Bonus Task
- **Correlation Analysis:**
  - Explore the correlation between trip distance and tip amount (without using direct correlation calculation).

### Visualizations
- Display the results of the common payment type, average tip amount, and best pickup locations using creative and efficient visualizations.
