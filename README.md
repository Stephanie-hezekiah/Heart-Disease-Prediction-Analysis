# HEALTHCARE ANALYSIS
Heart Disease Prediction Analysis

### PROJECT TITLE: Data Cleaning, Analysis, Querying and Visualization using Microsoft Excel and PowerBI Query

[Status](https://img.shields.io/badge/Status-Complete-success)

[Project Overview](#project-overview)

[Motivation](motivation)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning & Transformation](#data-Cleaning-and-transformation)
 
[Data Virtualization](#data-virtualization)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Contact](#contact)



### Project Overview
---
This project analyzes a COVID-19 patient dataset to uncover patterns in symptoms, demographics, and oxygen levels. It also implements predictive machine learning models to identify the key factors influencing COVID-19 diagnosis. The goal is to provide actionable insights and a reproducible workflow for researchers and data enthusiasts.

Key Metrics & Calculations

High Risk %: A dynamic DAX measure calculating the ratio of patients with heart disease against the total population.

Presence vs. Absence: Visual breakdown of diagnostic results.

Key Risk Indicators: Analysis of Chest Pain Type, Max HR, and Thallium levels.


### Motivation
---
COVID-19 continues to impact global health. By analyzing real patient data, we can:

Understand symptom patterns across genders and age groups

Explore correlations between oxygen levels, symptoms, and severity

Build predictive models to assist in early diagnosis

### Data Source
---
The dataset used in this project contains patient health information related to COVID-19 symptoms and diagnosis from Kaggle

Possible attributes in the dataset include:

Patient ID

Fever

Cough

Fatigue

Breathing difficulty

Other symptoms

COVID-19 test result or diagnosis

Dataset Type: Structured healthcare dataset

Format: Excel / CSV


### Tools Used
---

The following tools and technologies were used in this analysis:

Python

Pandas – Data manipulation and cleaning

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualizations

Jupyter Notebook – Analysis environment

GitHub – Project version control and portfolio hosting


### Data Cleaning & Transformation
---
Data Cleaning and Transformation

Before performing analysis, the dataset was cleaned and transformed to ensure accuracy and consistency.

The following steps were carried out:

Handling missing values

Removing duplicate records

Standardizing column names

Converting categorical variables into consistent formats

Ensuring correct data types for numerical and categorical fields

Example using Python

import pandas as pd

df = pd.read_excel("covid19_patient_symptoms_diagnosis.xlsx")

# Check missing values

df.isnull().sum()

# Remove duplicates

df = df.drop_duplicates()

# Convert column names to lowercase

df.columns = df.columns.str.lower()


### Data Virtualization
---
Data virtualization was used to create simplified views of the dataset that support easier analysis and visualization.

Examples include:

Creating filtered datasets for patients with positive diagnoses

Grouping symptom occurrences

Aggregating symptom counts for visualization

Example:

symptom_summary = df.groupby("diagnosis").sum()

### Exploratory Data Analysis
---

Gender Distribution of COVID Cases

Age Distribution of Infected Patients

Most Common Symptoms

Oxygen Level Comparison by Gender

Correlation Heatmap


### Contact
---
If you would like to collaborate, discuss this project, or connect professionally:

Name: Stephanie Hezekiah

Role: Data Analyst | Power BI Analyst

•	LinkedIn: https://www.linkedin.com/in/hezekiah-stephanie-11061422a/

•	Email: stephaniehezekiel@gmail.com

•	Portfolio: https://github.com/Stephanie-hezekiah
