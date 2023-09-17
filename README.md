# Store-sales-time-series-forecasting-LP3
Store sales time series forecasting project

## Overview

This repository contains a comprehensive analysis of store sales forecasting for Favorita, a prominent Ecuadorian grocery retailer. By leveraging time series forecasting techniques and various datasets, we aimed to uncover key sales patterns, identify influential factors, and develop accurate sales prediction models.

## Table of Contents

- [Introduction](#introduction)
- [Project Goals](#project-goals)
- [Exploring the Different Datasets](#exploring-the-different-datasets)
- [Data Collection](#data-collection)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Feature Importance](#feature-importance)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

## Introduction

In the ever-evolving world of retail, accurate sales forecasting is essential for optimizing inventory, improving operational efficiency, and enhancing customer satisfaction. This analysis dives into the realm of store sales analysis using time series forecasting, with the objective of providing Favorita with actionable insights to drive business growth.

## Objective of the Project

The primary objective of this article is to demonstrate the power of time series forecasting in analyzing and predicting store sales for Favorita, a prominent grocery retailer in Ecuador. By harnessing historical sales data, transaction records, and external factors such as oil prices and holidays, we aim to develop a robust model that can provide accurate sales predictions. Additionally, we seek to equip businesses with the tools and insights necessary to make informed decisions and enhance overall operational efficiency in the dynamic retail settings.

## Significance of the Project
This project improves sales predictions, empowers data-driven decision-making, enhances operational efficiency, and ultimately boosts customer satisfaction for businesses in the retail sector.

## Project Goals

- Analyze historical sales data, transaction records, and external factors.
- Develop accurate sales prediction models.
- Identify the impact of promotions, holidays, and economic factors on sales.
- Optimize marketing and inventory strategies.
- Provide recommendations for future sales forecasting efforts.

## Project Approach

The project followed the structured approach of the CRIPS-DM framework and ensured that all relevant steps are taken to achieve meaningful results.  The CRISP-DM (Cross-Industry Standard Process for Data Mining) framework is a widely used methodology for guiding data mining and data analysis projects.

## Data Description

The analysis includes the following datasets:

- Train data: comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
- Test data: the test data, has the same features as the train data excluding sales. This data will predict the target sales for the dates. The dates in the test data are for the 15 days after the last date in the training data.
- Transaction data: contains date, store_nbr and transaction made on that specific date.
Stores data: store metadata, including city, state, type, and cluster. 
- Oil data: daily oil price includes values during both the train and test data timeframes. 
holiday_eventts data: holidays and events, with metadata. 
- Additional Notes
 - Wages in the public sector are paid every two weeks on the 15th and on the last day of the month. Supermarket sales could be affected by this.
 - A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.



## Exploring the Different Datasets

We began by exploring various datasets, including sales, train, test, transaction, holiday events, and oil prices. This exploration helped us understand the data's features, uncover trends, and identify missing values.

## Data Collection

Data for this project was collected from multiple sources, including a database, OneDrive, and GitHub. Different datasets were retrieved from these sources, including oil prices, holiday events, store information, train and transaction data.

## Data Cleaning and Preprocessing

We conducted thorough data cleaning and preprocessing, addressing missing values and outliers to ensure data quality and reliability.

## Exploratory Data Analysis

We set our hypothesis and analysed by using T-test which is a tool used to determine if there is a significant difference between the means of two groups. We also set research questions that guided our study. Our exploratory data analysis involved visualizing data patterns, understanding the impact of promotions and holidays, and uncovering seasonality in sales data. We also identified the significance of different factors affecting sales.

## Modeling and Evaluation

We experimented with various forecasting models, including SARIMA, SARIMAX, ARIMA, AR, Linear Regression, Decision Trees, and Random Forests. Model evaluation led us to select Linear Regression as the most accurate for sales prediction.

## Feature Importance

Feature importance analysis helped us identify the most influential attributes affecting sales predictions. This guided feature selection and model optimization.

## Conclusion

In conclusion, this analysis equips Favorita with insights into store sales patterns, promotional impacts, and economic factors. We recommend integrating Linear Regression for accurate sales forecasting, optimizing promotions, and tailoring strategies around holidays.

## Recommendations

Our recommendations include leveraging feature importance, optimizing promotions, tailoring holiday sales strategies, monitoring economic factors, continual model refinement, and fostering collaboration between data scientists and business stakeholders.

By implementing these recommendations, Favorita can enhance its sales forecasting capabilities and drive business growth in the competitive retail landscape.

## References

This section includes research papers used in the project for reference and credibility.

|Code|Name of Project|Published Article|Deployed App|
|:---|:-------------:|:---------------:|-----------:|
|LP3 |Store sales Forecasting |https://medium.com/@rndcrabbe/store-sales-analysis-using-time-series-forecasting-abb2ded07c8d|Medium|


## Technologies Used

### Programming Language
- **Python**: Python was the primary programming language used for data analysis, preprocessing, modeling, and visualization. Python's extensive libraries and data science ecosystem made it a suitable choice for this project.

### Development Environment
- **Jupyter Notebook**: Jupyter Notebook served as the development environment for conducting data analysis, running code, and documenting the entire project. It allowed for an interactive and well-documented workflow.

### Data Manipulation and Analysis
- **Pandas**: Pandas is a powerful library for data manipulation and analysis. It was used for tasks such as data cleaning, aggregation, filtering, and feature engineering.

### Numeric and Scientific Computing
- **NumPy**: NumPy is a fundamental library for numerical and scientific computing in Python. It was employed for mathematical operations, array manipulation, and data handling.

### Data Visualization
- **Matplotlib**: Matplotlib is a versatile library for creating static, animated, and interactive visualizations in Python. It was used to generate various plots and charts to visualize data patterns.

### Machine Learning and Statistical Analysis
- **Scikit-Learn**: Scikit-Learn is a popular machine learning library in Python. It was utilized for building and evaluating predictive models, including linear regression, decision trees, and random forests.
- **Statsmodels**: Statsmodels is a library for estimating and interpreting statistical models. It was used for time series analysis, including SARIMA, ARIMA, AR and SARIMAX modeling.

These technologies collectively facilitated data exploration, cleaning, modeling, and visualization, enabling the successful completion of the store sales forecasting analysis.

## License

MIT Lincense

## Social Media
Medium

## Team Logo
<img src="https://github.com/reginacrabbe/Indian-startup-ecosystem-LP1-project/assets/137375344/650a71ad-0bbb-4aea-9bf3-ca5f93175dc1" width="100" height="100">

## Acknowledgement
Much appreciation to the entire Azubi Team for your continuous support and kudos to Cape Cod Team for their hard work and dedication.

## Authors
- Regina Naa Dedei Crabbe
- Kodwo Amissah-Mensah
- Alvin Momoh
- Alliyah
- Leon

### Contact
Regina Naa Dedei Crabbe

rndcrabbe@gmail.com
