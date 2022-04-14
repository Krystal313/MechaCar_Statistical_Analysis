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

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Based on the summary shown above, we can conclude the overall manufacturing lots seem to meet the design specifications for the MechaCar suspension coils given the variance of 62.29356. However, when looking at the individual lots, only lot 1 and 2 meet the design specification with the variance of 0.9796 and 7.4694.

## T-Tests on Suspension Coils

1. Briefly summarize your interpretation and findings for the t-test results, include screenshots of the t-test to support your summary.

![Avg_AllLot](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/060690c432e4dd44dbe52917194dd2e1515cb8e1/Resources/Avg_AllLot.png)

![Avg_Lot1](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/060690c432e4dd44dbe52917194dd2e1515cb8e1/Resources/Avg_Lot1.png)


![Avg_Lot2](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/060690c432e4dd44dbe52917194dd2e1515cb8e1/Resources/Avg_Lot2.png)

![Avg_Lot3](https://github.com/Krystal313/MechaCar_Statistical_Analysis/blob/060690c432e4dd44dbe52917194dd2e1515cb8e1/Resources/Avg_Lot3.png)

The t-test analysis of all three manufacturing lots revealed the true sample mean is 1498.78. We failed to reject the null hypothesis with the p-Value of 0.06028,  given it is higher than the significance level of 0.05. However, if we look at the individual lots, we can conclude that we could reject the null hypothesis for its p - value of 0.04186 with the true mean of sample = 1496.14. The true mean of sample for lots 1 and 2 were 1500 and 1500.2. However, we still failed to reject the null hypothesis for lots 1 and 2 given the p - values were 1 and 0.6072, which is higher than the significance level of 0.05. 
