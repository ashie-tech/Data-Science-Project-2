# Data-Science-Project-2

This project demonstrates a step-by-step approach to cleaning and preparing the dataset test.csv for further analysis or modeling. The cleaning process includes handling missing values, encoding categorical variables, and exploratory data analysis (EDA) visualizations.

Overview
The dataset test.csv contains raw data that requires cleaning before use. The goal of this process is to make the data consistent, complete, and suitable for statistical analysis or machine learning.

Steps in the Data Cleaning Process
Loading the Data
The CSV file test.csv is loaded into a pandas DataFrame for manipulation.

Initial Inspection

Checking for missing values in columns.

Understanding the data types and distributions.

Handling Missing Values

Numerical columns (e.g., Age) are filled with the median or mean to maintain central tendency.

Categorical columns (e.g., Embarked) are filled with the mode (most frequent value).

Rows with critical missing data can be dropped if necessary.

Encoding Categorical Variables

Convert categorical columns such as Sex and Embarked into numerical format for modeling.

For example, Sex is encoded as male = 0 and female = 1.

Embarked ports are encoded using label encoding or one-hot encoding.

Exploratory Data Analysis (EDA)

Visualize distributions and counts using seaborn plots such as histograms and count plots.

Create a correlation heatmap to understand relationships between features.

Final Dataset

The cleaned dataset is now ready for further analysis or to feed into machine learning algorithms.
