
# Projects

# Understanding Treatment Effects through Randomized Controlled Trials (RCTs) and Observational Trials: A Simulation Study on Odds Ratios and Logistic Regression

## Introduction

In this project, I delved into the complex relationship between treatment and survival in healthcare, utilizing both randomized controlled trials (RCTs) and observational trials. Through statistical simulations and logistic regression models, I uncovered the underlying dynamics that may have led to misleading conclusions about treatment effects.

## Project Overview

I focused on the challenges and complexities of analyzing treatment effects in healthcare. By conducting both RCTs and observational trials, I explored how treatment correlated with survival and emphasized the importance of considering confounding variables and context.

## Dataset Description

The simulated dataset I used consisted of the following key variables:

- **Treatment**: A binary variable indicating whether the treatment was administered (1) or not (0).
- **Age**: A continuous variable representing the age of the patients.
- **Death Probability**: Calculated based on age, with different probabilities for young and old patients.
- **Odds Ratios (OR)**: Derived from logistic regression models, representing the odds of an event occurring in the treatment group compared to the control group.
- **Success/Failure**: Outcome of the trials, indicating whether the treatment was successful or failed.

## Results

### Simulated Randomized Controlled Trials (RCTs)

- **Variables**: Age death threshold, young death probability, old death probability.
- **Outcome**: Dependency on age, with different odds ratios (OR) and success/failure rates.

### Observational Trials

- **Problem**: I found that many of the odds ratios were greater than one, suggesting a negative treatment effect.
- **Solution**: I included age as a confounding variable and excluded patients younger than a minimum treatment age.

### Logistic Regression Models

- **Single Variable Model**: Analysis using treatment as the only variable.
- **Multivariate Model**: Inclusion of age as another independent variable to improve the analysis.

## Conclusion

This project provided me with valuable insights into the robust analysis of treatment outcomes, serving as a resource for researchers, healthcare professionals, and statisticians. My findings emphasized the nuanced understanding of how treatment correlated with survival, shedding light on the challenges and potential solutions in interpreting treatment effects.

---

# Cardiovascular Diseases Risk Prediction

## Project Overview

This project aims to predict the risk of cardiovascular diseases using various health-related features. The analysis is conducted using Python, and the code includes data preprocessing, visualization, and modeling techniques.

## Data
The dataset includes the following features:

General Health (e.g., Poor, Very Good, Good, Fair, Excellent)

Checkup Frequency

Exercise

Heart Disease

Skin Cancer

Other Cancer

Depression

Diabetes

Arthritis

Sex

Age Category

Smoking History

Height (cm)

Weight (kg)

BMI

Alcohol Consumption

Fruit Consumption

Green Vegetables Consumption

Fried Potato Consumption

## Preprocessing

The preprocessing steps include:

Label Encoding for categorical variables

Handling missing values

Data transformation

## Visualization
Various visualizations, including violin plots for numerical variables, are created using Seaborn and Matplotlib.

## Results
The analysis provides insights into the relationships between different health factors and the risk of cardiovascular diseases. For example, the visualizations reveal patterns in BMI, alcohol consumption, and exercise habits in relation to heart disease. The predictive model developed in this project can be used to assess individual risks based on specific health parameters.

The results emphasize the importance of a healthy lifestyle and regular checkups in preventing cardiovascular diseases. The findings can be valuable for healthcare professionals, policymakers, and individuals seeking to understand and mitigate the risks associated with heart-related ailments.

## Conclusion
This project provides insights into the risk factors associated with cardiovascular diseases and offers a predictive model to assess individual risks. The analysis is detailed and can be followed by anyone interested in health data analysis.

---

# Salifort Motors HR Project

## Project Overview

This project is aimed at providing data-driven suggestions for the HR department of Salifort Motors. The HR department has collected data from employees and is interested in understanding the likely triggers that might compel an employee to leave the company. 
The primary objectives of the project are to analyze the collected data and construct a predictive model that could accurately forecast whether an employee might leave the company or not.

## Dataset

The dataset used in this project contains 14,999 rows and 10 columns. The variables in the dataset include:

- `satisfaction_level`: Employee-reported job satisfaction level [0–1]
- `last_evaluation`: Score of employee’s last performance review [0–1]
- `number_project`: Number of projects employee contributes to
- `average_monthly_hours`: Average number of hours employee worked per month
- `time_spend_company`: How long the employee has been with the company (years)
- `Work_accident`: Whether or not the employee experienced an accident while at work
- `left`: Whether or not the employee left the company
- `promotion_last_5years`: Whether or not the employee was promoted in the last 5 years
- `Department`: The employee’s department

## Analysis

The analysis involved the construction of a logistic regression model with assumptions that the outcome variable is categorical, observations are independent of each other, there is no severe multicollinearity among X variables, and there are no extreme outliers.

A new feature named `overworked` was created, which is a binary variable representing whether an employee is overworked or not. This was done by dropping the `satisfaction_level` and classifying being overworked as working more than 175 hours per month on average.

## Insights

The analysis revealed that employees are leaving the company as a result of poor management. Leaving is tied to longer working hours, many projects, and generally lower satisfaction levels. It can be ungratifying to work long hours and not receive promotions or good evaluation scores. There’s a sizeable group of employees at this company who are probably burned out. It also appears that if an employee has spent more than six years at the company, they tend not to leave.

## Conclusion

The ability to foresee potential employee exits is a valuable asset. It opens up the opportunity to identify possible factors contributing to their decision to quit. Given that recruiting new employees involves significant time and financial investments, 
this analysis aimed to support the company’s efforts to enhance employee retention, which would ultimately contribute to the overall efficiency and success of Salifort Motors.

---

# Airline Passenger Satisfaction Analysis
This project involves an exploratory data analysis and predictive modeling of airline passenger satisfaction based on a variety of factors such as flight distance, inflight wifi service, ease of online booking, and more. The goal is to create a model that accurately predicts passenger satisfaction and provides insights into the key factors that influence it.

# Loan Status Prediction
This project involves building a predictive model to determine whether a person should be granted a loan.

# Medical Expenses Prediction 
In this project, I've developed a model that predicts medical expenses based on personal health data.

# Optimizing Agricultural Production
 This project focuses on optimizing agricultural production using exploratory data analysis and machine learning techniques.

# Sum of Dice and Fibonacci Sequence 
This project involves creating a program that calculates the sum of dice and generates a Fibonacci sequence.

