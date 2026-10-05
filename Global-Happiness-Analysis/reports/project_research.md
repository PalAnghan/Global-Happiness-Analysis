# Global Happiness Analysis

## 1. Project Overview

This project analyzes global happiness using the World Happiness Report dataset.

The objective is to understand how happiness varies across countries and over time, and to identify the major social, economic, health, and personal factors associated with life evaluation.

The analysis focuses on:

- Global happiness trends over time
- Happiest and least happy countries
- Year-over-year changes in happiness
- Correlation between happiness and major factors
- Relationships between happiness and individual factors
- India-focused analysis
- Data-driven insights and conclusions


## 2. Research Questions

The project aims to answer the following questions:

1. Which countries have the highest life evaluation scores?
2. Which countries have the lowest life evaluation scores?
3. How has global happiness changed over time?
4. Which factors have the strongest relationship with happiness?
5. How strongly is happiness associated with GDP per capita?
6. How strongly is happiness associated with social support?
7. How strongly is happiness associated with healthy life expectancy?
8. How strongly is happiness associated with freedom to make life choices?
9. How strongly is happiness associated with generosity?
10. How strongly is happiness associated with perceptions of corruption?
11. How does India compare with other countries?
12. What major insights can be derived from the data?


## 3. Dataset

The analysis uses data from the World Happiness Report.

The dataset contains country-level observations across multiple years and includes life evaluation scores along with several explanatory factors.

Important variables include:

- Country name
- Year
- Rank
- Life evaluation (3-year average)
- Log GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption


## 4. Tools & Technologies

The project was developed using Python and Jupyter Notebook.

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

### Main Libraries

Pandas was used for data loading, cleaning, transformation, grouping, and analysis.

NumPy was used for numerical operations.

Matplotlib and Seaborn were used to create charts and visualize relationships between variables.


## 5. Data Preparation

The dataset was inspected before performing the analysis.

The data preparation process included:

- Checking dataset dimensions
- Inspecting column names
- Checking data types
- Identifying missing values
- Cleaning and standardizing data
- Selecting relevant columns
- Sorting observations by year
- Creating a country-level dataset using the latest available data

The latest available observation for each country was used when comparing countries.


## 6. Planned Analysis

The analysis included:

- Data loading
- Data inspection
- Data cleaning
- Descriptive statistics
- Exploratory data analysis
- Correlation analysis
- Country ranking analysis
- Year-wise trend analysis
- India-focused analysis
- Data visualization
- Key findings and conclusions


# 7. Key Findings

## 7.1 Happiest Countries

The latest available country-level analysis shows that Finland has the highest life evaluation score.

The top countries include:

| Rank | Country | Life Evaluation |
|---|---|---:|
| 1 | Finland | 7.76 |
| 2 | Iceland | 7.54 |
| 3 | Denmark | 7.54 |
| 4 | Costa Rica | 7.44 |
| 5 | Sweden | 7.25 |
| 6 | Norway | 7.24 |
| 7 | Netherlands | 7.22 |
| 8 | Israel | 7.19 |
| 9 | Luxembourg | 7.06 |
| 10 | Puerto Rico | 7.04 |

These countries demonstrate relatively high levels of life evaluation compared with the countries at the lower end of the ranking.


## 7.2 Least Happy Countries

Afghanistan has the lowest life evaluation score in the latest available data.

Some of the countries with the lowest scores include:

| Country | Life Evaluation |
|---|---:|
| Afghanistan | 1.45 |
| South Sudan | 2.82 |
| Sierra Leone | 3.25 |
| Rwanda | 3.27 |
| Malawi | 3.28 |
| Zimbabwe | 3.35 |
| Syria | 3.46 |
| Botswana | 3.46 |
| Central African Republic | 3.48 |
| Yemen | 3.53 |

The large difference between the highest and lowest values demonstrates substantial variation in life evaluation across countries.


## 7.3 Global Happiness Trend

The year-wise analysis shows that global average happiness has generally increased over the analyzed period.

The average life evaluation was approximately:

- 2011: 5.39
- 2016: 5.35
- 2020: 5.53
- 2021: 5.55
- 2023: 5.53
- 2024: 5.58
- 2025: 5.65

Although the trend is not continuously increasing every year, the overall direction is upward.

The highest average value in the analyzed data occurs in 2025.


## 7.4 Year-over-Year Change

The year-over-year analysis shows that global happiness experienced both increases and decreases.

The largest decreases occurred around:

- 2014
- 2016
- 2022
- 2023

The strongest increases occurred around:

- 2019
- 2020
- 2024
- 2025

The largest positive change in the analyzed period occurred in 2025, while 2014 showed the largest negative change.


# 8. Correlation Analysis

Correlation analysis was used to measure the strength of the linear relationship between life evaluation and the major explanatory factors.

The results were:

| Rank | Factor | Correlation |
|---|---|---:|
| 1 | Social Support | 0.71 |
| 2 | Log GDP per Capita | 0.68 |
| 3 | Healthy Life Expectancy | 0.66 |
| 4 | Freedom to Make Life Choices | 0.49 |
| 5 | Generosity | 0.43 |
| 6 | Perceptions of Corruption | 0.03 |


## 8.1 Social Support

Social support has the strongest correlation with happiness at approximately **0.71**.

The scatter plot shows a clear positive relationship.

This suggests that countries where people report stronger social support generally tend to have higher life evaluation scores.

However, correlation does not prove that social support directly causes higher happiness.


## 8.2 Log GDP per Capita

Log GDP per capita has the second strongest correlation with happiness at approximately **0.68**.

The scatter plot shows a positive relationship between economic conditions and life evaluation.

In general, countries with higher income levels tend to report higher happiness scores.

However, economic prosperity is only one component of overall well-being.


## 8.3 Healthy Life Expectancy

Healthy life expectancy has a correlation of approximately **0.66** with happiness.

The visualization shows a strong positive relationship.

This indicates that countries with better expected healthy lifespans generally tend to report higher life evaluation.


## 8.4 Freedom to Make Life Choices

Freedom to make life choices has a correlation of approximately **0.49**.

The relationship is positive but weaker than social support, GDP per capita, and healthy life expectancy.

This suggests that personal freedom is an important factor associated with happiness.


## 8.5 Generosity

Generosity has a correlation of approximately **0.43** with happiness.

This represents a moderate positive relationship.

Countries with higher reported generosity tend to have somewhat higher life evaluation scores, although the relationship is not as strong as the top three factors.


## 8.6 Perceptions of Corruption

Perceptions of corruption have a correlation of approximately **0.03** with happiness in this analysis.

This indicates a very weak linear relationship between the two variables in the analyzed dataset.

This result should be interpreted carefully because a weak correlation does not necessarily mean that corruption has no influence on well-being. Other factors, nonlinear relationships, measurement differences, or interactions between variables may affect the result.


# 9. Overall Findings

The analysis suggests that happiness is associated with multiple dimensions of people's lives.

The strongest relationships were observed for:

1. Social support
2. Economic prosperity
3. Healthy life expectancy

Personal freedom and generosity also showed positive relationships with life evaluation.

The results therefore suggest that happiness cannot be explained by a single factor. Instead, it is associated with a combination of social, economic, health, and personal conditions.


# 10. Limitations

There are several limitations to this analysis:

- Correlation does not imply causation.
- The dataset contains observations from different years.
- Some countries may have missing observations.
- Country-level averages may hide differences between individuals.
- The analysis mainly examines linear relationships.
- The factors may interact with each other.
- Different countries may have different cultural and reporting patterns.

## 11. Future Scope

The project can be extended in several ways.

Future analysis could include:

- Performing country-specific time-series analysis.
- Creating an interactive Streamlit dashboard for exploring happiness trends.
- Adding machine learning models to predict life evaluation scores.
- Performing advanced regression and feature-importance analysis.
- Studying nonlinear relationships between happiness and its influencing factors.
- Performing cluster analysis to group countries by happiness characteristics.
- Creating a dedicated India-focused analysis.
- Comparing India with neighboring countries.
- Adding newer World Happiness Report data when available.


# 12. Conclusion

This project analyzed global happiness using historical and country-level data.

The analysis found substantial differences in life evaluation across countries. Finland recorded the highest life evaluation score in the latest available data, while Afghanistan recorded the lowest.

The year-wise analysis suggests that global average happiness has generally increased over the analyzed period, although several years experienced temporary declines.

Correlation analysis identified social support as the strongest factor associated with happiness, followed by log GDP per capita and healthy life expectancy. Freedom to make life choices and generosity also showed positive relationships, while perceptions of corruption showed very little linear correlation in this dataset.

Overall, the analysis demonstrates that global happiness is a multidimensional concept associated with social relationships, economic conditions, health, freedom, and other factors.

The project provides a data-driven overview of global happiness and demonstrates how Python-based data analysis and visualization can be used to discover meaningful patterns in real-world datasets.