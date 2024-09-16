---

# Regression Project - R Programming

## Project Overview
This project was part of a linear regression course, focusing on analyzing hotel booking data to understand the factors influencing the average daily rate (ADR). It involved data preprocessing, building regression models, and interpreting results using R programming.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Objectives](#objectives)
- [Methods and Analysis](#methods-and-analysis)
- [Results](#results)
- [Conclusions](#conclusions)
- [Files in This Repository](#files-in-this-repository)
- [How to Use](#how-to-use)
- [Authors](#authors)

## Data Source
The dataset used for this project describes various parameters involved in hotel bookings, including the number of days between booking and arrival, room types, meal plans, country of origin, and special requests.

## Objectives
The project's main objectives included:
1. Identifying relationships between the different factors (e.g., lead time, number of adults, room type) and the average daily rate (ADR).
2. Building a regression model to predict the ADR based on the selected variables.
3. Testing various statistical assumptions and validating the regression model.

## Methods and Analysis
The project was split into two main parts:
### Part A
1. **Data Selection**: Choosing the hotel booking dataset.
2. **Data Preprocessing**: Cleaning the data, removing outliers, and handling categorical variables.
3. **Descriptive Statistics**: Analyzing variables to understand their distribution and relationships.
4. **Correlation Analysis**: Identifying potential relationships between variables.

### Part B
1. **Model Building**: Using R to build linear regression models.
2. **Model Validation**: Testing model assumptions like normality, linearity, and homoscedasticity.
3. **Improving the Model**: Introducing interaction terms and variable transformations to optimize model performance.

## Results
The regression analysis identified key factors influencing the ADR, including lead time, number of adults, and room type. Several models were built and tested, with the final model selected based on statistical criteria such as AIC (Akaike Information Criterion).

## Conclusions
The analysis confirmed that specific variables like lead time and room type have a significant impact on the ADR. Adjusting the model with interaction terms and transformations helped in improving its predictive power.

## Files in This Repository
- **Regression Part A.pdf**: Detailed analysis of the data selection, preprocessing, and descriptive statistics.
- **Regression Part B.pdf**: The modeling process, model validation, and final results.
- **Regression Part A+B.R**: R script containing the code used in both parts of the project.
- **Regression Part B - Finale.R**: The finalized R script for model building and validation in Part B.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/RoiAzrai/Regression-Project-R-Programming.git
    ```
2. Load the R scripts in your R environment to review the code and analysis.
3. Review the PDFs for detailed explanations and interpretations of the results.

## Authors
- **Roi Azrai (Roi Ezrai)** - [GitHub](https://github.com/RoiAzrai)
- **Shani Gueta**

---
