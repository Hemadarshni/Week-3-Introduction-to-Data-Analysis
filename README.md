# Week-3-Introduction-to-Data-Analysis
## Project Title: Sales Data Analysis using Python (Pandas)
## Project Overview

This project focuses on analyzing a real-world sales dataset using Python and Pandas. The goal is to understand basic data analysis concepts such as loading data, cleaning data, calculating statistics, and generating insights like total sales and the month with the highest sales.

This project is part of Week 3: Introduction to Data Analysis – Working with Real Data.

## Project Objectives

Learn how to use the Pandas library for data analysis

Read and explore data from a CSV file

Clean and prepare real-world data

Calculate key sales metrics

Identify the month with the highest sales

Generate a simple and readable analysis report

## Setup and Installation Instructions
Step 1: Install Required Libraries

Make sure Python is installed, then run:

pip install pandas
Step 2: Project Files

Ensure the following files are present in your project folder:

├── sales_analysis.py
├── sales_data.csv
├── analysis_report.md
├── requirements.txt
└── screenshots/
Step 3: Run the Program

You can run the analysis using:

python sales_analysis.ipynb

Or execute the notebook cells if using Jupyter Notebook.

## Code Structure Explanation

sales_analysis.py: Contains all Python code for loading, cleaning, and analyzing the sales data

sales_data.csv: Input dataset containing sales records

analysis_report.md: Written explanation of analysis steps and findings

requirements.txt: Lists required Python libraries

screenshots/: Contains screenshots of program output and analysis

## Data Analysis Steps

Loaded the CSV file using Pandas

Checked dataset information, missing values, duplicates

Converted the Date column to a datetime format

Created a new Month column from the Date

Calculated key metrics such as:

Total sales

best-selling product

Average sales

Highest and lowest sales

Grouped data by month to find the month with the highest sales

Month with Highest Sales (Key Insight)

The dataset was grouped by the newly created Month column, and total sales were calculated for each month using Pandas. The month with the highest total sales was identified using the idxmax() function.

## Screenshots

Screenshots of the following are included in the screenshots/ folder:

Dataset loaded successfully

Month column creation

Output showing highest sales month

Final analysis results

## Technical Requirements Fulfilled

✔ Used Pandas to load and analyze CSV data

✔ Handled missing values safely

✔ Calculated more than three metrics

✔ Created a clean and formatted output

✔ Added comments explaining each step

## What I Learned

How to work with real datasets using Pandas

How to clean and prepare data for analysis

How to extract useful insights from raw data

How to document and present analysis professionally

