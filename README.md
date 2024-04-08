# Crime-Data-Analysis

## Overview
This project focuses on analyzing a dataset of crime reports from a city. The data includes various attributes related to each crime incident, such as the offense code, description, district, reporting area, and the date and time of the occurrence. The analysis aims to uncover patterns and trends in crime incidents over time, identify the most common types of crimes, and determine the distribution of crime occurrences across different times of the day, days of the week, and months of the year.

## Dataset
The dataset, named `crime.csv`, consists of over 319,000 entries with 17 columns detailing each crime incident. It includes both numerical and categorical data types, such as the offense code, offense description, district, date and time of occurrence, and location coordinates.

## Data Preprocessing
The preprocessing steps involved:
- Identifying and dropping duplicate entries to ensure data integrity.
- Converting the `OCCURRED_ON_DATE` column from an object to a datetime data type for easier analysis of time-related trends.
- Handling missing values, particularly in the `DISTRICT`, `SHOOTING`, `UCR_PART`, `STREET`, `Lat`, and `Long` columns.

## Exploratory Data Analysis (EDA)
The EDA focused on understanding the composition of the data, including:
- The most common crimes based on offense group and description.
- The distribution of crimes over the years, days of the week, and hours of the day.
- Identification of unique values across different columns to understand data granularity and categorization.

## Key Insights
Some key insights gained from the analysis include:
- Motor Vehicle Accident Response, Larceny, and Medical Assistance were identified as the top three most common offense groups.
- The data showed a higher number of crimes reported on Fridays and during the late afternoon to evening hours.
- An examination of the monthly crime distribution indicated that crime rates fluctuate over the year, with peaks observed during the summer months.

## Usage
To run this project, you will need to have Python installed along with the following libraries:
- NumPy
- Matplotlib
- Pandas
- Seaborn

1. Import the necessary libraries.
2. Load the `crime.csv` dataset.
3. Follow the preprocessing steps to clean the data.
4. Conduct exploratory data analysis using various visualization techniques to uncover patterns in the data.
