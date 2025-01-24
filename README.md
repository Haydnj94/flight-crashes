# Presentation = https://www.canva.com/design/DAGdALtY4vs/u9sKasInpJb-dGjVbLBJnQ/edit?utm_content=DAGdALtY4vs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


# README: Aircraft Crash Analysis Repository

## Overview

This repository analyzes aircraft crash data to uncover trends, patterns, and insights. It includes data cleaning, exploratory analysis, visualization, and hypothesis testing steps to provide actionable insights.

## Steps Performed

1. Import and Initialization

Imported libraries: pandas, numpy, seaborn, and fuzzywuzzy for data analysis and visualization.

Configured display settings and warnings for a clean working environment.

2. Data Loading

Loaded the dataset using pandas from the provided CSV file.

3. Data Cleaning

Standardized column names and converted all text data to lowercase.

Replaced missing values with "unknown" and filled numerical fields with zeros where necessary.

Converted relevant columns to numeric data types for proper analysis.

4. Exploratory Analysis

Conducted summary statistics to understand the dataset.

Examined relationships between variables such as crash locations, aircraft size, and total fatalities.

5. Pivot Table Creation

Created a pivot table with a multi-index of country and cat_size to aggregate crash data.

Used sum as the aggregation function to calculate total occurrences.

6. Visualization Enhancements

Designed presentation-ready graphs to visualize trends such as crash occurrences over time.

Applied modern styling for high-quality visuals suitable for professional use.

7. Insights and Findings

Observed that most crashes occurred within 10 km of airports for all aircraft sizes.

Noted differences in crash patterns by aircraft size, with small and medium aircraft more likely to crash in valleys or mountains and large aircraft more likely to crash in water.

Suggested implications about domestic versus international routes based on these patterns.

8. Final Refinements

Polished text, visuals, and summaries for presentation.

Ensured code and documentation are clear and professional.

## Outputs

Cleaned datasets ready for further analysis.

High-quality visualizations for presentations.

Detailed insights into aircraft crash trends.
