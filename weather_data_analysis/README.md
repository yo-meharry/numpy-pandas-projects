# Weather Data Analysis using Pandas & NumPy

## Project Overview
This project analyzes a time-series weather dataset containing hourly weather conditions.  
The dataset includes temperature, humidity, wind speed, visibility, pressure, and weather conditions.

## Tools & Technologies
- Python
- Pandas
- NumPy

## Dataset Information
The dataset contains:
- 8784 rows (hourly data for a year)
- 8 columns:
  - Date/Time
  - Temperature (°C)
  - Dew Point Temperature
  - Relative Humidity (%)
  - Wind Speed (km/h)
  - Visibility (km)
  - Pressure (kPa)
  - Weather Condition

## Steps Performed

### 1. Data Loading
- Loaded CSV file using Pandas

### 2. Data Exploration
- Used .head(), .shape, .columns, .dtypes
- Checked unique values and counts

### 3. Data Cleaning
- Checked for null values
- Verified data consistency

### 4. Data Analysis
Performed various operations such as:
- Finding unique values
- Filtering data using conditions
- Using groupby() for aggregation
- Calculating mean, variance, and standard deviation
- Sorting and conditional filtering

### 5. Key Analysis Questions
- Unique wind speed values
- Number of clear weather records
- Instances of specific wind speed
- Mean visibility
- Standard deviation of pressure
- Weather-wise average values
- Filtering based on multiple conditions

## Key Insights
- "Mainly Clear" and "Mostly Cloudy" are the most frequent weather conditions  
- Average visibility is around 27.66 km  
- Snow and Rain conditions appear frequently in the dataset  
- Weather conditions significantly impact temperature and humidity levels  
- High wind speeds are often associated with lower temperatures  

## What I Learned
- Data cleaning and preprocessing using Pandas  
- Filtering and grouping data efficiently  
- Performing statistical analysis  
- Handling real-world datasets  
- Writing structured and readable analysis code  

