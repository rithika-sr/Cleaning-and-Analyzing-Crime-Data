# Cleaning and Analyzing Crime Data (IE6400 Project 1)

## Project Overview
In this project, we delve into a real-world dataset containing crime data from 2020 to present, exploring various crime trends, patterns, and underlying factors. Our primary objective is to cleanse and analyze the dataset to gain meaningful insights that can potentially enhance public safety strategies.

## Data Source
The dataset is acquired from a Data.gov repository, encompassing a comprehensive record of reported crimes from 2020 to present. It includes details on incident times, locations, and victim demographics.

## Repository Contents
- `data_cleaning.ipynb`: Jupyter notebook for data cleaning and preliminary analysis.
- `data_analysis.ipynb`: Jupyter notebook for detailed exploratory data analysis (EDA).
- `crime_data.csv`: Original dataset used for the analysis.

## Environment and Libraries
- **Python**: Main programming language used.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** and **Seaborn**: For data visualization.
- **ARIMA**: For forecasting crime trends.

## Analysis Workflow
1. **Data Acquisition**: Download the dataset from the Data.gov repository.
2. **Data Inspection**: Identify missing values and incorrect data types.
3. **Data Cleaning**:
   - Handling missing values by imputation or removal.
   - Converting data types for accurate analysis.
   - Removing redundant or irrelevant columns.
4. **Exploratory Data Analysis (EDA)**:
   - Visualizing crime trends from 2020 to present.
   - Analyzing seasonal patterns and crime distribution across regions.
   - Investigating correlations with economic factors.
5. **Advanced Analysis**:
   - Forecasting future crime rates using the ARIMA model.

## Key Findings
- The crime rates have shown both seasonal variations and significant anomalies possibly related to major events or policy changes.
- The most common type of crime is vehicle theft, which has seen a substantial decline towards the end of the dataset.
- Economic factors show low direct correlation with crime rates, suggesting other external factors may play a more significant role.

## Conclusion
This project not only provides a clear picture of the crime landscape over recent years but also offers a foundation for future studies to build upon, particularly in terms of policy formulation and resource allocation.

