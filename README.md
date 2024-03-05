# Credit Dataset Analysis

This project involves conducting an exploratory data analysis (EDA) on a credit dataset. The dataset contains information about credit applications, including both categorical and numeric variables.

## Features

- **Data Import:** Utilized the `readr` package in R to import the credit dataset from a CSV file.
- **Descriptive Statistics:** Calculated descriptive statistics such as mean, median, mode, maximum, and minimum for numeric variables.
- **Quantiles:** Determined the quantiles (25% and 75%) for the 'amount' variable to understand the distribution.
- **Correlation Analysis:** Investigated the relationships between numeric variables using a correlation matrix.
- **Chi-Squared Test:** Conducted a chi-squared test to analyze the relationship between categorical variables, specifically between 'credit_history' and 'default'.
- **Decision Tree Model:** Built a decision tree model using the `rpart` package to predict credit defaults based on other attributes.

## Techniques and Concepts Used

- **Exploratory Data Analysis (EDA):** Explored the dataset to understand its structure, identify variables, and detect missing values.
- **Descriptive Statistics:** Calculated statistical measures to summarize the central tendency and dispersion of numeric variables.
- **Quantitative Analysis:** Employed quantiles to analyze the distribution of a numeric variable.
- **Correlation Analysis:** Assessed the strength and direction of relationships between numeric variables using correlation coefficients.
- **Chi-Squared Test:** Determined the independence between categorical variables by comparing observed and expected frequencies.
- **Decision Tree Modeling:** Implemented a machine learning algorithm to predict credit defaults based on attribute values.

## Scope of the Project

The project aims to provide valuable insights into credit applications, assisting financial institutions in making informed decisions and enhancing their risk assessment processes. By analyzing the patterns and trends in the dataset, the project facilitates understanding the factors influencing credit defaults.

## Repository Structure

- **data:** Contains the credit dataset used for analysis.
- **scripts:** Includes R scripts for importing data, conducting EDA, calculating statistics, and building the decision tree model.
- **README.md:** Provides an overview of the project, techniques used, and its scope.

## Future Enhancements

- **Feature Engineering:** Explore additional features or transformations to improve the predictive performance of the decision tree model.
- **Model Evaluation:** Conduct comprehensive evaluation metrics for the decision tree model to assess its accuracy and robustness.
- **Interactive Visualization:** Incorporate interactive visualizations to facilitate better understanding and exploration of the dataset.

## Further contributions:
Feel free to contribute to the project by suggesting improvements, reporting issues, or extending its functionality.

