# Pymaceuticals Inc. Study Analysis

## Overview

This project involves analyzing a dataset from a study conducted by Pymaceuticals Inc. to evaluate the effects of different drug regimens on tumor volume in mice. The analysis includes data cleaning, statistical summary generation, and various visualizations to derive insights from the study.

## Files

- `Mouse_metadata.csv`: Contains metadata about the mice, including Mouse ID, Drug Regimen, Sex, Age, and Weight.
- `Study_results.csv`: Contains the study results, including Mouse ID, Timepoint, Tumor Volume, and Metastatic Sites.

## Dependencies

- pandas
- matplotlib
- scipy

## Analysis Steps

1. **Data Loading and Merging:**
   - Load the mouse metadata and study results from CSV files.
   - Merge the two datasets into a single DataFrame for analysis.

2. **Data Cleaning:**
   - Identify and remove duplicate entries to ensure data integrity.
   - Verify the number of unique mice before and after cleaning.

3. **Descriptive Statistics:**
   - Calculate summary statistics (mean, median, variance, standard deviation, and SEM) for tumor volume by drug regimen.
   - Generate a summary statistics table.

4. **Visualizations:**
   - Generate a bar plot showing the total number of mouse timepoints for each drug regimen.
   - Generate a pie plot showing the distribution of male and female mice.

5. **Quartiles, Outliers, and Boxplots:**
   - Calculate the final tumor volume for selected drug regimens.
   - Identify potential outliers using IQR.
   - Generate box plots to visualize the distribution of tumor volumes.

6. **Correlation and Regression Analysis:**
   - Generate a scatter plot to analyze the relationship between mouse weight and tumor volume for the Capomulin regimen.
   - Calculate the correlation coefficient and perform linear regression analysis.

## Conclusion
The analysis reveals insights into the effectiveness of different drug regimens on reducing tumor volumes in mice. It also highlights the correlation between mouse weight and tumor volume, particularly for the Capomulin regimen.
