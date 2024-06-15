# CRIME DATA ANALYSIS

This repository contains the Jupyter Notebook for Project 1 by Group 17, focused on the analysis and cleaning of a dataset as part of the coursework for IE6400 (Fundamentals Of Data Analytics).

## Project Overview

In this project, we perform extensive data cleaning and analysis on a provided dataset. The notebook details each step of the process, from handling missing values to adjusting data types and removing outliers. Our primary focus is to prepare the data for subsequent analytical tasks and ensure its integrity.

## Data Cleaning Highlights

- **Handling Missing Values**: We addressed columns with significant numbers of missing entries, such as the 'Vict Sex' column, by removing entries lacking data.
- **Value Correction**: We standardized the entries in the 'Vict Sex' column to 'M' for Male, 'F' for Female, and 'X' for Others. Similarly, we corrected implausible values (like negative numbers) in the 'Vict Age' column.

## Analysis Performed

The notebook includes various analytical techniques to explore the dataset further:
- Identification and removal of outliers.
- Detailed exploratory data analysis to understand the distribution and relationships within the data.

## Tools Used

- Python
- Libraries: Pandas, NumPy

## Installation

To run this project, clone the repository and ensure you have Jupyter Notebook installed. You can install the necessary Python libraries using the following command:

```bash
pip install -r requirements.txt
