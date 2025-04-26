# Student-Performance-Analysis

## Overview
This repository contains a comprehensive analysis of student performance data, exploring the relationships between demographics, study habits, extracurricular involvement, and academic outcomes. The analysis includes data exploration, visualizations, and a linear regression model to predict GPA.

## Table of Contents

1. [Project Description](#project-description)
2. [Dataset](#dataset)
3. [Analysis](#analysis)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Future Work](#future-work)
7. [Dependencies](#dependencies)


## Project Description

The goal of this project is to analyze factors influencing high school students' GPA and to build a predictive model. We examine how variables such as study time, absences, tutoring, parental support, and extracurricular activities impact academic performance.

## Dataset

- **Source:** Student performance dataset (2,392 entries, 15 variables)
- **Key Features:**
  - **Demographics:** Age, Gender, Ethnicity, Parental Education
  - **Study Habits:** Weekly study time, Absences, Tutoring
  - **Parental Involvement:** Parental Support
  - **Extracurricular:** Sports, Music, Volunteering, General activities
  - **Performance:** GPA (2.0–4.0 scale), GradeClass (A–F)

## Analysis

- **Exploratory Data Analysis (EDA):**
  - Descriptive statistics and distributions
  - Correlation heatmap to identify variable relationships
  - Box plots to compare GPA across different groups
  - Line plots illustrating trends (e.g., study time vs. GradeClass)

- **Modeling:**
  - Train-test split (80/20)
  - Linear Regression on features: StudyTimeWeekly, Absences, Tutoring, Extracurricular, ParentalSupport
  - Evaluation metrics: MSE, R-squared

## Results

- **Key Findings:**
  - **Absences** show a strong negative correlation with GPA (-0.92).
  - **Tutoring** and **Extracurricular** participation positively influence GPA.
  - **Linear Regression** model achieved an **R² of ~0.94** and **MSE of ~0.05**.

- **Visualizations:**
  - GPA distribution histogram
  - Correlation heatmap
  - Box plots (GPA by activity participation)
  - Scatter plot of True vs. Predicted GPA

## Conclusion

The analysis confirms that attendance, tutoring, and extracurricular involvement are significant predictors of academic success. The linear regression model reliably predicts student GPA based on these factors, explaining over 93% of variance.

## Future Work

- Explore non-linear models (e.g., Random Forest, Gradient Boosting)
- Incorporate additional socio-economic variables
- Perform cross-validation and hyperparameter tuning
- Deploy the model as a simple web application

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly
- jupyter




