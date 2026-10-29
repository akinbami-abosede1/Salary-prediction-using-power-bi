# Salary Prediction Using Power BI

## Project Overview

This project explores the relationship between years of work experience and salary using Power BI. It applies simple linear regression to estimate salary based on a selected number of years of experience.

The dashboard combines data visualization, DAX calculations, and interactive parameters to help users explore how salary estimates change with work experience.

## Project Objectives

- Analyze the relationship between years of experience and salary.
- Visualize the relationship between the two variables using a scatter plot.
- Calculate the slope and intercept required for a simple linear regression model.
- Build an interactive salary prediction feature that estimates salary for different levels of experience.
- Demonstrate how Power BI can be used for basic predictive analytics.

## Tools and Technologies

- **Microsoft Power BI** — Dashboard development and data visualization.
- **DAX (Data Analysis Expressions)** — Calculation of regression components and predicted salary.
- **Linear Regression** — Estimation of the relationship between years of experience and salary.

## Project Implementation

### 1. Data Visualization

A scatter plot was created to examine the relationship between years of experience and salary. This visualization helps reveal the direction and general pattern of the relationship between the variables.

### 2. Linear Regression Calculations

DAX measures were developed to calculate the slope and intercept of the regression equation.

The simple linear regression model is expressed as:

                          Y=a+bX

Where:

- \(Y\) = Predicted salary
- \(a\) = Intercept
- \(b\) = Slope
- \(X\) = Years of experience

The slope represents the estimated change in salary associated with an additional year of experience, while the intercept represents the model's estimated salary when years of experience equals zero.

### 3. Interactive Salary Prediction

A numeric range parameter was created in Power BI, allowing users to select years of experience from 1 to 30.

The selected value is used as the input for the regression model to calculate and display the corresponding predicted salary.

This feature enables users to explore salary estimates interactively without manually changing the underlying data.

## Key Features

- Scatter plot showing the relationship between experience and salary.
- DAX measures for calculating the regression slope and intercept.
- Interactive experience selection from 1 to 30 years.
- Dynamic salary estimation based on the selected experience.
- Power BI dashboard for exploring salary trends and predictions.

## Key Learnings

Through this project, I gained practical experience in:

- Creating interactive dashboards in Power BI.
- Writing DAX measures for statistical calculations.
- Applying simple linear regression to a real-world analytical problem.
- Using numeric range parameters for interactive analysis.
- Translating mathematical concepts into an interactive business intelligence solution.

## Limitations

The predictions depend on the quality and characteristics of the dataset used to build the model. The model considers years of experience as its predictor and does not account for other factors that can influence salary, such as education, job role, industry, location, or skills.

The predicted values are estimates and should not be interpreted as guaranteed salaries.

## Project Files

- **Power BI Dashboard (.pbix):** Contains the dashboard, DAX measures, visualizations, and interactive salary prediction functionality.
- **Dataset:** The data used to analyze the relationship between years of experience and salary, subject to the dataset's usage permissions.
- **Dashboard Screenshots:** Visual previews of the completed project, if included in the repository.

## Conclusion

This project demonstrates how Power BI can be used beyond descriptive reporting to perform basic predictive analysis. By combining scatter plot visualization, regression calculations, and interactive parameters, the dashboard allows users to explore estimated salaries at different levels of work experience.

Tools: Power BI

