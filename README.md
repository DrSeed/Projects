<<<<<<< HEAD


# README for Salifort Motors HR Project

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
>>>>>>> a58f28b (salifort_mortors_project)
