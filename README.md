# Chicago Crime Data Analysis

## Overview
This project analyzes crime data from Chicago between 2008 and 2012, combining crime records with census data to identify patterns, trends, and insights using Python.

The goal is to explore how crime varies over time, location, and type, and to practice real-world data cleaning, transformation, and analysis.

---

## Dataset
The data used in this project comes from official public datasets:

- Chicago Crime Data:  
  https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

- Chicago Census Data:  
  https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

Note: The crime dataset is large (>2GB), so only data from **2008–2012** is used for this analysis.

---

## Project Steps

### 1. Data Preparation
- Loaded and explored large-scale datasets
- Converted date columns to datetime format
- Created new time-based features (Year, Month, Day, Hour)
- Filtered data to focus on the 2008–2012 period

---

### 2. Data Cleaning
- Checked for duplicates (none found)
- Identified missing values across multiple columns
- Applied different strategies:
  - Removed rows with missing geographical data (coordinates)
  - Removed rows with missing administrative data (district, ward, community area)
  - Kept non-critical missing values (e.g., location description)

---

### 3. Exploratory Data Analysis (EDA)
- Analyzed dataset structure and key variables
- Identified most common crime types:
  - Theft
  - Battery
  - Narcotics
  - Criminal Damage
- Explored common locations:
  - Street
  - Apartment
  - Sidewalk
- Investigated patterns over time and across categories

---

## Key Insights
- Crime is concentrated in specific types and locations
- Temporal patterns (year/month/hour) help explain crime behavior
- Data cleaning decisions significantly impact analysis results
- Large datasets require thoughtful filtering and preprocessing

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## How to Run
1. Download the datasets from the links above
2. Place them in the same folder as the notebook:
   - `chicago_crime.csv`
   - `chicago_census.csv`
3. Open the notebook and run all cells

---

## What I Learned
- Handling and cleaning large real-world datasets
- Making decisions about missing data and data quality
- Extracting insights from complex datasets
- Structuring analysis workflows for clarity and reproducibility

---

## Author
Juan Andrade  
AI & Machine Learning Student – IT-Högskolan 
