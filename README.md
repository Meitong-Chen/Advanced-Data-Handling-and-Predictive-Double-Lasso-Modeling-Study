# Advanced Data Handling and Predictive Double Lasso Modeling Study

## Introduction
This repository documents my personal exploration into sophisticated data handling techniques and predictive modeling using real-world medical and prescription data. The study focuses on meticulous data preprocessing, merging, and the application of statistical models to understand and predict healthcare outcomes.

## Process Overview

### Data Cleaning and Preprocessing
- **Loading Data**: Data is loaded into pandas DataFrames from CSV files.
- **Handling Duplicates**: Duplicate records are identified and removed to ensure data integrity.
- **Filtering Age Range**: Data is filtered to include patients aged 40 to 75, aligning with the study's target demographic.
- **Missing Value Management**: Missing values are assessed and handled through removal or imputation to prepare the dataset for analysis.
- **Column Management**: Unnecessary columns that do not contribute to analysis are dropped to streamline the dataset.

### Data Merging and Predictive Modeling
- **Merging Criteria**: Data from medical records and prescription details are merged based on common identifiers to create a comprehensive dataset.
- **Date Validation**: Ensures that medical claims are appropriately timed after prescriptions to maintain logical sequencing of medical events.
- **Predictive Modeling**: Implements statistical and machine learning models to predict outcomes based on the cleaned and merged data.

## Technologies Used
- **Python**: Primary programming language for scripting and analysis.
- **Pandas**: For data manipulation and merging.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For visualization of the data.
- **SciPy**: For statistical analysis in Python.

## Setup and Installation
To replicate the analysis or explore the preprocessing steps, ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scipy
