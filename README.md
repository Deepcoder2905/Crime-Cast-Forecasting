# Crime-Cast Forecasting

Crime-Cast Forecasting is a machine learning project that aims to predict crime occurrence using a dataset obtained from Kaggle. The project involves performing Exploratory Data Analysis (EDA), preprocessing the data, and training several machine learning models to forecast crimes.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [EDA and Preprocessing](#eda-and-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Dependencies](#dependencies)

## Project Overview

The goal of this project is to forecast the likelihood of crimes occurring in various locations based on historical data. The models used include Random Forest, XGBoost Classifier, Bagging Classifier with Decision Tree, and Gradient Boosting Classifier. We compare these models based on accuracy, precision, recall, and other relevant metrics.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com). It contains the following features:

- **Location**: The place where the crime occurred.
- **Cross_Street**: The cross street near the crime location.
- **Latitude** and **Longitude**: Geographical coordinates of the crime location.
- **Date_Reported** and **Date_Occurred**: The reported and actual dates of the crime.
- **Time_Occurred**: The time when the crime occurred.
- **Area_ID**: An identifier for the area where the crime occurred.
- **Area_Name**: The name of the area where the crime occurred.
- **Reporting_District_no**: The number of the reporting district.
- **Part 1-2**: Classification of the crime as Part 1 or Part 2.
- **Modus_Operandi**: The method or technique used to commit the crime.
- **Victim_Age**, **Victim_Sex**, **Victim_Descent**: Information about the victim.
- **Premise_Code** and **Premise_Description**: The location or building type where the crime occurred.
- **Weapon_Used_Code** and **Weapon_Description**: Information about any weapons used in the crime.
- **Status** and **Status_Description**: The status of the crime case (open, closed, etc.).
- **Crime_Category**: The type of crime committed.

**Link to dataset:** [Kaggle Dataset](https://www.kaggle.com/code/zimbaster/22f2000876-notebook-t22024/input)

## EDA and Preprocessing

Exploratory Data Analysis (EDA) was performed to understand the distribution and relationships between various features. Key steps in EDA included:

- Visualizing crime trends over time.
- Analyzing correlations between features like victim demographics, crime types, and locations.
- Identifying missing data and handling them.

In preprocessing, we performed:

- Data cleaning (handling missing values, outliers).
- Encoding categorical variables.
- Scaling numerical features.
- Splitting the data into training and test sets.

## Modeling

Several machine learning models were implemented to forecast crime occurrences:

1. **Random Forest** - A robust ensemble method.
2. **XGBoost Classifier** - Known for its high performance in structured/tabular data.
3. **Bagging Classifier with Decision Tree** - Combines multiple decision trees for better predictions.
4. **Gradient Boosting Classifier** - An ensemble method that builds models sequentially.

Each model was evaluated based on various performance metrics such as accuracy, F1-score, and ROC-AUC.

## Results

The models were compared on several metrics, with the following highlights:

- **Random Forest**: Have Accuracy of 90%.
- **XGBoost Classifier**: Excelled in [Accuracy].
- **Bagging Classifier**: Performed well on [Recall].
- **Gradient Boosting Classifier**: Best trade-off between precision and recall.

## Dependencies

To run this project, you will need the following dependencies:

- Python
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn


