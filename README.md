# Analysing Pharmaceutical Sales Data

## Overview

This project focuses on analysing pharmaceutical sales data using Python, Pandas, and Matplotlib. The goal is to explore sales patterns, identify top-selling drug categories, and understand how pharmaceutical sales change over time.

## Dataset

The dataset is obtained from Kaggle: [Pharma Sales Data](https://www.kaggle.com/milanzdravkovic/pharma-sales-data).

It contains pharmaceutical sales records at different time intervals:

- **Daily sales** (`salesdaily.csv`)
- **Hourly sales** (`saleshourly.csv`)
- **Weekly sales** (`salesweekly.csv`)
- **Monthly sales** (`salesmonthly.csv`)

The daily dataset records sales for different drug categories using ATC (Anatomical Therapeutic Chemical) codes. Each ATC code is represented by a separate column, and the sales quantity for each category is recorded for each day. The dataset also contains date-related information, such as year, month, hour, and weekday name.

## Tools and Technologies

- Python
- Pandas — for data loading, filtering, grouping, and analysis
- Matplotlib — for data visualization
- Jupyter Notebook — for writing and executing analysis

## Project Objectives

The analysis aims to answer the following questions:

1. What are the total sales quantities for each drug category (ATC code)?
2. Which individual drug brands have the highest total sales?
3. Which three drug categories have the highest sales in January 2015, July 2016, and September 2017?
4. Which drug category has the highest sales in 2017?
5. Which drug category has the highest average daily sales?
6. Are respiratory drugs (R03) sold more during specific months?

## Initial Data Exploration

The analysis began by loading the daily sales dataset into a Pandas DataFrame and examining its rows and columns to understand the dataset's structure.

The initial exploration identified the ATC-coded sales columns and the date-related columns needed for further analysis.

## Project Structure

```text
Analysing-pharmaceutical-sales-data/
│
├── data/
│   ├── salesdaily.csv
│   ├── saleshourly.csv
│   ├── salesmonthly.csv
│   └── salesweekly.csv
│
├── notebooks/
│   └── pharmaceutical_sales_analysis.ipynb
│
└── README.md
```

## Key Findings

*To be added after documenting the results of the analysis and visualizations.*

## Conclusion

This project uses data analysis techniques to explore pharmaceutical sales across drug categories and time periods. It provides an opportunity to practice data cleaning, filtering, aggregation, statistical analysis, and visualization using Python.

project url: https://roadmap.sh/projects/pharmaceutical-sales-dat