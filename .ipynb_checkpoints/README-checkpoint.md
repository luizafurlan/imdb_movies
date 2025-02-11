# IMDB Dataset Analysis Project

## Overview
This project focuses on analyzing a dataset from IMDB to answer three key business questions:
    1. How has cinema evolved over the last 60 years?
    2. What characteristics are most associated with a movie winning an Oscar?
    3. Which features can help predict movie revenues?
The CRISP-DM (Cross Industry Standard Process for Data Mining) methodology is employed throughout the project to guide the data science process efficiently.

## CRISP-DM Process
1. Business Understanding
    • Objective: Identify trends and key indicators in the film industry that contribute to movie success, particularly in revenue and accolades like the Oscars.
    • Questions:
        ◦ How has movie production changed over decades?
        ◦ What attributes influence the success of Oscar-winning films?
        ◦ Which movie characteristics correlate with higher box office revenues?
2. Data Understanding
    • Data Source: IMDB dataset
    • Description: The dataset contains information about movies including release date, genre, revenue, Oscar nominations, and wins.
    • Initial Insights: Decades of data coverage, variety of movie attributes.
3. Data Preparation
    • Cleaning: Handle missing values, remove duplicates.
    • Transformation: Convert dates, standardize numerical attributes.
    • Feature Selection: Identify relevant features for analysis and modeling.
4. Modeling
    • Approach:
        ◦ For revenue prediction, regression models.
        ◦ For Oscar-winning and nominations characteristics, descriptive and inferential statistics.
    • Tools: Python libraries such as Pandas, Matplotlib, Seaborn, Scikit-learn.
5. Evaluation
    • Metrics:
        ◦ Revenue prediction: MSE, MAE, RMSE, R²
    • Outcome: Evaluate model performance and validate assumptions.
6. Deployment
    • Documentation: Comprehensive findings report.
    • Presentation: Key insights and recommendation presentation.

## What's included

This project contains two folders and 3 notabooks. In the Data folder, there is the data used in the analysis downloaded in [Kaggle](https://www.kaggle.com/datasets/raedaddala/imdb-movies-from-1960-to-2023/data), while in the Final Dataset folder there is the data merged and cleaned. 
Also, the 3 notebooks was constructed to Gathering Data, Cleaning and Undestand the Dataset, and finally, the analysis and prediction revenue. The steps of thsi process were separated to a better organization.  

## Conclusion

This project aims to provide actionable insights emphasizing the film industry’s evolution, characteristics of successful movies, and predictive features for revenue estimation. By following the CRISP-DM methodology, the analysis ensures a structured and systematic approach to data mining and insights generation.