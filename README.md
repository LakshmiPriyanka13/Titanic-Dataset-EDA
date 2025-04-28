# Titanic-Dataset-Exploratory Data Analysis

This project involves performing a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic dataset from Kaggle.
The goal is to understand the dataset's structure, clean missing values, visualize key patterns, and identify important features related to survival.

## Files in the Repository
- Titanic Dataset EDA.ipynb : Jupyter Notebook containing all EDA steps.
- train.csv : Training dataset containing passenger information along with survival status.
- test.csv : Testing dataset (without survival labels).
- gender_submission.csv : A sample submission file used in Kaggle competitions.

## EDA Steps Performed
Data Loading and Inspection
   - Viewed first few rows, checked shape and data types.
   - Identified missing values in key columns.
Data Cleaning
   - Filled missing Embarked values with the mode.
   - Filled missing Age values with the median.
   - Dropped the Cabin column due to too many missing values.
Univariate Analysis
   - Plotted histograms for Age and Fare.
   - Plotted count plots for categorical variables: Survived, Pclass, Sex, and Embarked.
Bivariate Analysis
   - Compared survival rate across Sex and Pclass using bar plots.
  - Used KDE plots to compare age distributions between survivors and non-survivors.
Correlation Analysis
   - Computed correlation between numerical variables to understand their relationships.

## Summary of Key Findings
Gender:
   - Females had a much higher survival rate compared to males.
Class:
   - Passengers from higher classes (Pclass = 1) had better survival chances.
Age:
   - Younger passengers had a slightly higher survival probability.
Embarked Port:
   - Most passengers embarked from port 'S'.
   - Slight variations in survival rates depending on the port of embarkation.
Fare:
   - Passengers who paid higher fares generally had better survival chances.
Missing Data Handling:
   - Critical missing data (Age, Embarked) was handled using appropriate imputations.
   - Cabin was dropped to avoid noise due to excessive missing values.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

