# EDA_NYC_TAXI




# NYC Taxi Data Analysis

![NYC Taxi Animation](NYCTAXI.gif)

## Overview
This project explores NYC taxi trip data to uncover key insights about trip patterns, passenger trends, and fare distributions. The dataset contains **83,691** entries with **20 columns**, including timestamps, location IDs, trip distances, and fare details.

## Key Findings

### 1. Data Quality & Missing Values
- Some columns, such as `VendorID`, `store_and_fwd_flag`, and `passenger_count`, have missing values.
- The `ehail_fee` column contains no data and can be dropped for analysis.

### 2. Trip Distance & Fare Analysis
- The majority of trips are short, with a median trip distance of approximately **1.5 miles**.
- Fare amounts are highly skewed, with most trips costing between **$5 and $20**.
- Some outliers indicate unusually high fares, likely due to long-distance trips or tolls.

### 3. Passenger Count Distribution
- The most common passenger count is **1**, indicating that NYC taxis are primarily used for solo trips.
- A small fraction of trips have more than **3 passengers**, suggesting limited group travel.

### 4. Tip Amount Trends
- Customers generally tip **15-25%** of the fare.
- Higher fares tend to receive higher absolute tips but lower percentage-wise.

### 5. Temporal Patterns
- Peak hours occur between **5 PM - 8 PM**, coinciding with evening commutes.
- Weekend trips show a higher proportion of leisure rides compared to weekday business trips.

