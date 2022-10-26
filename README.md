## Heart Failure Analysis - README
This project aims to analyze and gain insights from a dataset containing clinical records of heart failure patients. We will perform data preparation, cleaning, and visualization to understand the distribution and relationships of various attributes. The goal is to identify patterns, trends, and factors that may affect the survival rate of heart failure patients.

## Table of Contents
* Project Overview
* Data Preparation and Cleaning
* Exploratory Data Analysis & Visualization
* Inferences and Conclusions
* Future Work
**1. Project Overview**
The project analyzes a dataset containing clinical records of heart failure patients. We will load the data using the Pandas library, perform data cleaning and preparation operations, and visualize the data to gain insights. The main objectives are to understand the distribution of patients' ages, gender, and survival status, as well as the prevalence of various medical conditions and abnormalities among the patients.

**2. Data Preparation and Cleaning**
We start by loading the dataset from a CSV file using Pandas and create a copy named "heart_failure_df" to preserve the raw data for analysis. Then, we perform the following data preparation and cleaning operations:
Renaming the "DEATH_EVENT" column to "patient_dead" for convenience.
Dropping the "time" column as it is not necessary for our analysis.
Converting the "age" column from float to int data type.
Converting boolean columns like "anaemia," "diabetes," "high_blood_pressure," "smoking," and "patient_dead" to bool data type for convenience.
Changing the values of the "sex" column to "Male" or "Female" instead of numeric codes.
Converting the "platelets" column to represent platelet count in kilo-platelets/mcL.
Checking for null values, but there are none in the dataset.

**3. Exploratory Data Analysis & Visualization**
In this section, we analyze the data to gain insights and visualize various attributes:
Distribution of age of heart failure patients using histograms.
Distribution of gender using a pie chart.
Death rate of heart failure patients using a pie chart.
Death rate by age group and gender using countplots.
Prevalence of various medical conditions and abnormalities using countplots.
Pairwise relationships between different attributes using a pair plot.
Distribution plots for numeric columns to check for skewness.

**4. Inferences and Conclusions**
Based on the analysis, we draw several inferences and conclusions:
The dataset contains 299 heart failure patients, with more male patients (194) than female patients (105).
Most patients are in the age group of 60-65, followed by 50-55. The number of patients declines after the age of 65.
The death rate during the follow-up period is 32.1%.
Patients aged 60-65 have the highest number of deaths.
The death rate is almost equal between male and female patients.
Abnormal Ejection Fraction is the most common factor among heart failure patients, while abnormal Platelets Count is the least common.
Medical record values are not normally distributed, with platelet count, ejection fraction, and creatinine level being right-skewed, and sodium level being left-skewed.
Smoking habit has little impact on the life expectancy of a heart failure patient.

**5. Future Work**
There are several potential future improvements for this project:
Gather data from a wider geographical area to confirm the findings on heart failure patients' common factors.
Analyze the number of patients who died based on their specific medical conditions and abnormalities.
Investigate the relationship between clinical records like "Ejection Fraction" and "Creatinine Level" and their impact on patient survival.
Implement machine learning models to predict the life expectancy of heart failure patients based on clinical records.
Please note that the conclusions drawn from this analysis are based on the data available and may not be generalized to the entire population. Further research and data collection may be required for more comprehensive insights.

**References**
Dataset: Heart Failure Clinical Records Dataset
Life Expectancy in Pakistan: World Bank Data
Explanation and Measurement Units for Attributes: BMC Medical Informatics & Decision Making

**Author**

Project by: ANSHUL CHAUHAN
