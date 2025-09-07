Project Description

This project is about predicting employee salaries based on different features such as years of experience, job title, education level, country, and race. The dataset used is “Salary_Data_Based_country_and_race.csv”, which contains salary-related records across different demographics and job attributes.

The notebook applies data preprocessing, cleaning, visualization, and machine learning techniques to explore the relationship between education, experience, and other factors with salary. It then builds predictive models to estimate salaries.

Key Steps in the Project

Data Preprocessing

Import required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

Load and inspect the dataset.

Drop unnecessary columns and handle missing values (median for numeric, mode for categorical).

Detect and remove outliers using the IQR method.

Standardize categorical values (e.g., converting variations of “Bachelor’s” or “Master’s” into consistent labels).

Remove duplicates.

Exploratory Data Analysis (EDA)

Visualize salary distribution.

Create scatterplots such as Salary vs. Years of Experience.

Check correlations between features.

Feature Engineering

Standardize and clean education levels.

Encode categorical variables for modeling.

Modeling

Split the dataset into training and testing sets.

Train models (likely regression models, tuned via GridSearchCV).

Evaluate performance of models on predicting salaries.

Goal of the Project

The main objective is to build a predictive model that estimates employee salaries based on key factors such as experience, education, and demographics.
This can be useful for:

Companies benchmarking salaries.

Job seekers understanding salary expectations.

Policy-making in diversity and wage gap analysis.
