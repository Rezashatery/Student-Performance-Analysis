# Student Performance Analysis

## Project Description

This project aims to analyze the data of unsuccessful students using the "StudentsPerformance.csv" dataset. The analysis focuses on identifying factors that contribute to student failure and provides insights into the demographic characteristics of unsuccessful students.

## Dataset

The dataset used in this project is "StudentsPerformance.csv". It contains information about student demographics, test preparation courses, and scores in math, reading, and writing.

## Code Overview

The code performs the following steps:

1. **Data Loading and Exploration:**
   - Loads the dataset using pandas.
   - Explores the data using `shape`, `info`, and `describe` functions.
   - Analyzes unique values in categorical columns.

2. **Data Visualization:**
   - Creates visualizations using matplotlib and seaborn to understand the distribution of scores and the relationship between variables.
   - Generates pie charts, histograms, violin plots, and box plots.

3. **Outlier Detection:**
   - Identifies outliers in math, reading, and writing scores using the Interquartile Range (IQR) method.
   - Analyzes the demographic characteristics of outliers.

4. **Success Status:**
   - Calculates the average score for each student.
   - Creates a new column indicating success status based on the average score.

5. **Unsuccessful Student Analysis:**
   - Filters the data to focus on unsuccessful students.
   - Encodes categorical columns using LabelEncoder for correlation analysis.
   - Calculates and visualizes the correlation between variables for unsuccessful students.
   - Calculates and visualizes failure rates for different demographic categories.

## Usage

1. Ensure you have the necessary libraries installed:
