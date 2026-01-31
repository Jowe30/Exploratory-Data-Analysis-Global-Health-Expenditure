# Exploratory-Data-Analysis-Global-Health-Expenditure
## Global Health Expenditure Analysis — Project Summary

### Overview

This project analyzes global health expenditure trends across countries and years using a structured data science workflow. The objective was to understand how health spending evolves over time, identify cross-country patterns, and present insights through an interactive dashboard built with Plotly and Dash.

### Data Exploration

The dataset contains:
1. Country Name
2. Country Code
3. Annual Health Expenditure values recorded over multiple years

Initial exploration focused on:
- Inspecting data structure and variable types
- Identifying year-based columns and transforming them into an analyzable format
- Understanding the coverage of countries and time periods
- Detecting missing and inconsistent values across countries and years.
To enable time-series analysis, the dataset was reshaped from wide format to long format, allowing each row to represent a country–year observation.

### Data Cleaning & Preparation
Several preprocessing steps were applied to ensure data quality:
1. Converted year values from string to numeric format for proper filtering and visualization
2. Removed countries with missing health expenditure records to maintain consistency
3. Standardized column names for clarity and usability
4. Ensured all expenditure values were numeric and suitable for aggregation
These steps resulted in a clean, structured dataset optimized for both statistical analysis and interactive visualization.

### Exploratory Data Analysis (EDA)
The exploratory phase focused on understanding the structure, coverage, and quality of the Global Health Expenditure dataset obtained from the World Bank.

Key steps included:
1. Inspecting the dataset’s dimensions, column structure, and data types
2. Identifying the time range and country coverage
3. Detecting missing values across country–year observations
4. Checking for duplicate records
5. Assessing overall data completeness and consistency
To enable time-series analysis, the dataset was reshaped from a wide format (years as columns) into a long format, where each row represents a single country–year observation. This transformation made it easier to filter, aggregate, and visualize trends over time.

Initial exploration revealed that several countries had incomplete reporting in recent years, highlighting gaps in global health expenditure data.

### Data Visualization

Visualization was used to uncover patterns and communicate insights effectively.

The analysis included:
- Scatter plots to examine the distribution of health expenditure per capita over time
- Country-level trend analysis to observe changes in spending across years
- Aggregated metrics (average, minimum, and maximum expenditure) to provide context alongside trends.

To enhance interactivity and usability, a dynamic dashboard was developed using Plotly and Dash, featuring:
1. Country selection slicers
2. Year range filtering
3. KPI cards summarizing key expenditure metrics
4. A time-series line chart showing health expenditure trends

All visual components update dynamically based on user selections, enabling deeper exploration of global health expenditure patterns.

### Key Insights

- Health expenditure trends vary significantly across countries and regions
- Long-term spending patterns become clearer when viewed through interactive time filtering
- Aggregated metrics (average, max, min) provide useful context alongside trend analysis
- Interactive dashboards significantly enhance exploratory analysis compared to static charts.

### Tools & Technologies
- Python
- Pandas and Numpy for data manipulation
- Plotly for interactive visualizations
- Dash for dashboard development.

### Conclusion
This project demonstrates a full end-to-end data analysis workflow, from raw data exploration and cleaning to advanced interactive visualization. The final dashboard enables intuitive exploration of global health expenditure trends and serves as a scalable foundation for further analysis, such as regional comparisons or policy-focused insights.
