# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview
This project is part of a Data Analyst Internship and involves performing Exploratory Data Analysis (EDA) on the Titanic dataset provided by Kaggle. The objective is to explore the data, clean it, visualize key patterns, and derive insights related to passenger survival.

## Dataset
- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- File used: train.csv

## Tools Used
- Python
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Key Steps Performed
1. *Data Loading*: Read the Titanic dataset using pandas.
2. *Initial Exploration*: Viewed basic stats and checked for missing values.
3. *Data Cleaning*:
   - Filled missing values in Age and Embarked.
   - Dropped the Cabin column due to excessive missing data.
4. *Exploratory Visualizations*:
   - Count plots for survival distribution by gender and class.
   - Histograms for age and fare distributions.
   - Boxplots for age and fare vs survival.
   - Heatmap to show feature correlations.
   - Pairplot for multivariate relationships.

## Key Insights
- *Gender*: Females had a much higher survival rate than males.
- *Class*: Passengers in 1st class were more likely to survive.
- *Fare*: Higher fares tended to correlate with higher survival rates.
- *Age*: Children and younger passengers had slightly higher survival rates.
- *Correlation*: Pclass, Fare, Sex showed strong influence on survival.

## Files Included
- Titanic_EDA_Complete.ipynb – Jupyter Notebook with full EDA code and visuals.
- (Optional) Titanic_EDA_Complete.pdf – Exported PDF version of the notebook.
- `README.md
