# Computing Intelligence and Applications

**Student Registration Number:** 224008709

## Project Overview
This repository contains my assignment for the "Computing Intelligence and Applications" course. The project focuses on predicting and understanding customer behavior by analyzing a Customer Churn dataset. 

## Link to Notebook
You can view the full code and outputs for this assignment directly in my notebook:
* [View my Kaggle Notebook Here](./assigment02-224008709.ipynb)

## Tasks Completed in this Assignment
1. **Data Loading:** Imported the dataset into a pandas dataframe.
2. **Data Preprocessing:** 
   * Converted the `Churn` attribute from Yes/No to binary 1/0.
   * Corrected data types (e.g., converting `TotalCharges` to float).
   * Handled missing values by identifying and dropping nulls.
3. **Exploratory Data Analysis (EDA):**
   * **Demographics:** Analyzed the impact of Gender, Senior Citizen status, Partners, and Dependents on churn.
   * **Services:** Investigated how having a Phone Service affects customer retention.
   * **Payments:** Explored churn rates based on Contract Type, Paperless Billing, and Payment Methods.

## Libraries Used
* `pandas`: For data manipulation and analysis.
* `numpy`: For numerical operations.
* `matplotlib.pyplot`: For creating foundational plots.
* `seaborn`: For advanced and aesthetically pleasing statistical visualizations.