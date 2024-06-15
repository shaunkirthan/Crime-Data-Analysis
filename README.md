# CRIME DATA ANALYSIS

This repository contains the Jupyter Notebook focused on the analysis and cleaning of a crime-related dataset as part of the coursework for IE6400 (Fundamentals Of Data Analytics).

## Project Overview

This project involves rigorous data cleaning and analysis of a crime data set provided by the course instructors. We've meticulously documented each step in our Jupyter Notebook, demonstrating how we handle missing data, adjust data types, and tackle statistical outliers. The goal is to refine the dataset to a state that supports robust analytical studies, ensuring data integrity and usability for predicting trends and patterns in crime incidents.

## Data Cleaning Highlights

- **Handling Missing Values**: Significant missing data in critical columns like 'Vict Sex' were identified and addressed by omitting rows that lacked essential information, ensuring a more reliable dataset for analysis.
- **Value Correction**: We enforced data consistency in categorical data such as 'Vict Sex' by standardizing values to 'M' (Male), 'F' (Female), and 'X' (Other). For 'Vict Age', we removed nonsensical entries, such as negative values, to uphold the dataset’s logical integrity.
 https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.iteratorshq.com%2Fblog%2Fdata-cleaning-in-5-easy-steps%2F&psig=AOvVaw0lxyaX3PeRNrPUtSIriKCO&ust=1718576916616000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCOCUpIfU3oYDFQAAAAAdAAAAABAR![image](https://github.com/shaunkirthan/Crime-Data-Analysis/assets/122591072/79652a56-5ab6-42ac-8eff-57c8725991ef)

## Analysis Performed

Our analytical approach is methodical and varied to ensure a comprehensive understanding of the crime data:
- **Outlier Detection and Removal**: Employed statistical techniques to identify and exclude data points that deviate excessively from the mean, which could potentially skew the analysis.
- **Exploratory Data Analysis (EDA)**: Conducted thorough EDA to uncover underlying patterns, relationships, and anomalies in the data. This includes visualization of data distributions, correlation studies between different variables, and preliminary hypothesis testing.

## Tools Used

- **Python**: Chosen for its versatility and the extensive support of libraries for data analysis.
- **Libraries**: 
  - **Pandas**: Utilized for efficient data manipulation and cleaning.
  - **NumPy**: Employed for numerical operations on data arrays.
  - **Matplotlib/Seaborn**: Used for creating static, interactive, and animated visualizations to better understand the data.
