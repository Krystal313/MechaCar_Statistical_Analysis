# MechaCar_Statistical_Analysis

# Overview of the project
Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG

![MechaCarMpg_LinearRegression](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/d71f9226c651dedef81e39dd14693882136eabfd/Resources/MechaCarMpg_LinearRegression.png)
![MechaCarMpg_Summary](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/846e5d51e1dafaa4a28ec6c3716e59f941b571b8/Resources/MechaCarMpg_Summary.png)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle weight, spoiler angle and AWD provided the non - random amount of variance to the mpg values in the dataset. 

2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the liner model is not considered to be zero because the p-value of linear regression is 5.35e-11, which it is smaller than significance level of 0.05%. 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, because this linear model has multiple r-squared value of 0.7149, which means approximately 71% of all mpg predictions will be correct using this linear model. 

## Suspension Coil
Total Summary

![SuspensionCoil_TotalSummary](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/53c939689bb9871f138da96836c85a6768329046/Resources/SuspensionCoil_TotalSummary.png)

Lot Summary

![SuspensionCoil_LotSummary](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/53c939689bb9871f138da96836c85a6768329046/Resources/SuspensionCoil_LotSummary.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Based on the summary shown above, we can conclude the overall manufacturing lots seem to meet the design specifications for the MechaCar suspension coils given the variance of 62.29356. However, when looking at the individual lots, only lot 1 and 2 meet the design specification with the variance of 0.9796 and 7.4694.

## T-Tests on Suspension Coils
briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
