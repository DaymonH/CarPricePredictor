# Used Car Price Predictor Notebook

## Overview
This Jupyter Notebook contains a series of steps for predicting used car prices using machine learning.

## Setup and Libraries
Ensure you have the necessary libraries installed. The notebook uses:
- `keras`
- `pandas`
- `pandasql`
- `zip_to_state`
- `plotly`
- `numpy`
- `scipy`
- `seaborn`
- `sklearn`

## Phases in the Notebook
1. **Phase 1: Data Collection**
   - Extract Training Data from Parquet File
   - Preview the Dataset's Schema

2. **MLOps Phase 2: Data Ingestion**
   - Data ingestion framework not implemented in this tutorial

3. **MLOps Phase 3: Data Storage**
   - Already extracted data from BigQuery; typically stored in a Cloud Storage Bucket

4. **MLOps Phase 5: Exploratory Data Analysis (EDA)**
   - Analysis of missing values per column
   - Categorical Data Column Analysis
   - Numerical Data Column Analysis
   - Histograms and frequency distribution plots

5. **Data Pipeline (Preparation and Wrangling)**
   - Feature selection and data cleaning steps
   - Imputation and outlier handling
   - Data type conversion and formatting

6. **MLOps Phase 6: Feature Engineering**
   - Turning zip codes into state fields
   - DataFrame merging for preprocessing
   - Handling missing values and redundant entries

7. **MLOps Phase 7: Model Development**
   - Feature identification and label assignment
   - Splitting the dataset into training and evaluation subsets
   - Fitting the training subset to a Decision Tree Regressor model
   - Showing feature importance metrics
