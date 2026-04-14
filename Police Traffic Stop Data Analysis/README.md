# Police Traffic Stop Data Analysis using Python (Pandas)

## Project Overview
This project analyzes a real-world police traffic stop dataset using Python and Pandas. The goal is to explore patterns in traffic violations, driver behavior, searches, and stop outcomes.

The dataset contains information about traffic stops such as driver gender, age, violation type, search conducted, and stop duration.

---

## Dataset Information
The dataset includes the following columns:

- stop_date
- stop_time
- driver_gender
- driver_age_raw
- driver_age
- driver_race
- violation_raw
- violation
- search_conducted
- search_type
- stop_outcome
- is_arrested
- stop_duration
- drugs_related_stop

---

## Data Cleaning Steps
- Removed column with all missing values (country_name)
- Checked and handled missing values in multiple columns
- Converted stop duration into numeric values for analysis
- Handled categorical and numerical data separately
- Explored dataset structure using .info() and .isnull()

---

## Analysis Performed

### 1. Speeding Analysis by Gender
- Compared how many men vs women were stopped for speeding

### 2. Search Behavior Analysis
- Checked whether gender affects search probability during stops
- Used grouping and aggregation techniques

### 3. Stop Duration Analysis
- Converted categorical duration into numeric values
- Calculated mean stop duration

### 4. Violation vs Age Distribution
- Compared age distribution for different violation types using .groupby().describe().

---

## Key Insights
- Males are stopped significantly more for speeding than females
- Search actions are much more common for male drivers
- Speeding is the most common violation type
- Age distribution varies slightly across violation categories

---

## Tools Used
- Python
- Pandas
- Jupyter Notebook

---

## Skills Demonstrated
- Data Cleaning
- Handling Missing Values
- GroupBy Operations
- Value Counts Analysis
- Feature Mapping

---
