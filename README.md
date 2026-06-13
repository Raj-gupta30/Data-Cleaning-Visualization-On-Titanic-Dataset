# Titanic Data Cleaning and Visualization

## Project Overview

This project focuses on cleaning and analyzing the Titanic dataset. The main objective is to perform data preprocessing, handle missing values, detect outliers, remove duplicates, and create visualizations to uncover meaningful insights about passenger survival patterns.

The project was completed as part of a Data Science internship task on Data Cleaning and Visualization.

---

## Dataset

The dataset contains information about Titanic passengers, including:

- Passenger details
- Age
- Gender
- Passenger class
- Fare
- Embarkation port
- Survival status

Dataset Source:
https://www.kaggle.com/competitions/titanic/data

---

## Objectives

- Understand the structure of raw data
- Handle missing values
- Identify and treat outliers
- Remove duplicate records
- Perform exploratory data analysis
- Create visualizations to communicate findings

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning Steps

### Missing Values

- Filled missing values in the Age column using the median.
- Filled missing values in the Embarked column using the mode.
- Removed the Cabin column due to a large number of missing values.

### Duplicate Records

- Checked for duplicate entries and removed them where necessary.

### Outlier Detection

- Used boxplots to identify outliers.
- Applied the IQR method to handle extreme values in numerical features.

---

## Visualizations Created

### Survival by Gender

Analyzed survival rates among male and female passengers.

### Survival by Passenger Class

Compared survival rates across different passenger classes.

### Age Distribution

Explored the age distribution of passengers.

### Fare Distribution

Examined the distribution of ticket fares.

### Correlation Heatmap

Visualized relationships between numerical and encoded categorical features.

---

## Key Findings

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers had a higher chance of survival compared to lower classes.
- Fare showed a positive relationship with survival.
- Most passengers were between 20 and 40 years old.
- Passenger class and gender were among the most influential factors affecting survival.

---

## Project Structure

├── Titanic_Data_Cleaning.ipynb
├── Titanic.csv
├── README.md
└── images/

---

## Future Improvements

- Build a machine learning model to predict survival.
- Create an interactive dashboard using Streamlit.
- Perform advanced feature engineering.

---

## Author

Raj Gupta
