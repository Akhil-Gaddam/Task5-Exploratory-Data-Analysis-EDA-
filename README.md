# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective
Perform Exploratory Data Analysis on the Titanic dataset to extract insights using statistical and visual methods.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

# Files


## Steps Performed
 - Loaded Titanic dataset (`train.csv`).  
 - Performed initial data checks (`.info()`, `.describe()`, `.isnull().sum()`).  
 - Handled missing values in 'Age' and 'Embarked'.  
# Plotted:
- Histograms for 'Age' and 'Fare'.
- Countplots for 'Survived', 'Pclass', and 'Survived' vs 'Pclass'.
- Boxplots for 'Survived' vs 'Age'.
- Scatterplot for 'Age' vs 'Fare'.
- Heatmap for correlation analysis.
- Pairplot for multivariate exploration.


## Key Findings
- Most passengers are young adults.
- Fares are right-skewed with few high-value outliers.
- Higher survival rates in females and first-class passengers.
- Fare and Pclass correlate with survival.
- No major multicollinearity among numeric features.

## Dataset
- Titanic Dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).

## Outcome
This task improved skills in using visual and statistical methods to find patterns, trends, and anomalies in real-world data, preparing for predictive modeling.
