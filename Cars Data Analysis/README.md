# Cars Data Analysis using Python (Pandas)

## Project Overview
This project focuses on analyzing a dataset of different cars with their specifications using Python and Pandas. The dataset includes information such as car make, model, engine size, horsepower, mileage, weight, and pricing.

The main goal of this project is to clean the data, handle missing values, and perform basic data analysis to extract meaningful insights.

---

## Dataset Information
The dataset contains the following columns:

- Make
- Model
- Type
- Origin
- DriveTrain
- MSRP
- Invoice
- EngineSize
- Cylinders
- Horsepower
- MPG_City
- MPG_Highway
- Weight
- Wheelbase
- Length

Total Rows: 432  
Total Columns: 15  

---

## Data Cleaning Steps
- Checked for null values in all columns
- Filled categorical missing values with mode
- Filled numerical missing values with mean
- Converted MSRP and Invoice from string ($ format) to numeric
- Handled inconsistent data types

---

## Data Analysis Performed

### 1. Null Value Handling
All missing values were identified and treated appropriately.

### 2. Value Counts
Counted occurrences of different car manufacturers (Make).

### 3. Filtering Data
Filtered cars based on conditions such as:
- Origin = Asia or Europe
- Weight less than or equal to 4000

### 4. Data Transformation
- Increased MPG_City values by 3 using vectorized operations

---

## Key Learnings
- Data cleaning techniques
- Handling missing values
- Filtering and conditional selection in Pandas
- Data transformation using vectorized operations
- Basic exploratory data analysis (EDA)

