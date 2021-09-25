# MechaCar_Statistical_Analysis

## Overview of Project
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Deliverables:
This new assignment consists of three technical analysis deliverables and a proposal for further statistical study. You’ll submit the following:

1. ***Deliverable 1:*** Linear Regression to Predict MPG
2. ***Deliverable 2:*** Summary Statistics on Suspension Coils
3. ***Deliverable 3:*** T-Test on Suspension Coils
4. ***Deliverable 4:*** Design a Study Comparing the MechaCar to the Competition

## Deliverable 1
### Linear Regression to Predict MPG

![alt tag](https://github.com/elrvra/MechaCar_Statistical_Analysis/blob/main/Resources/Deliverable1pic.png)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- The vehicle length and vehicle ground clearance provided a non-random amount of variance to the mpg values on the MechaCar prototype

2. Is the slope of the linear model considered to be zero? Why or why not?

- The slope of the linear model is not considered zero as the p-value: 5.35e-11 is less than the assumed significance level of 0.05%

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- This linear model does in fact predict mpg of MechaCar prototypes effectively as the r-squared value of 0.7149, about 71% of all mpg predictions will be determined by this models

## Deliverable 2
### T-Test on Suspension Coils

![alt tag](https://github.com/elrvra/MechaCar_Statistical_Analysis/blob/main/Resources/Deliverable2pic.png)

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- The current manufacturing data does meet the design specification of not exceeding 100 pounds per square inch, as the variance of the coils is 62.29 PSI when looking at the total population

- Additionally, when looking at the lot summary, we can see that lot 1 and lot 2 specifically does meet the design specification of not exceeding 100 pounds per square inch, as the variance of the coils is .98 and 7.47 respectively; however, lot 3 is well over with a variance = 170..29

## Deliverable 3
### T-Test on Suspension Coils

![alt tag](https://github.com/elrvra/MechaCar_Statistical_Analysis/blob/main/Resources/Deliverable3pic.png)

1. Briefly summarize the interpretation and findings for the t-test results.

-  The true mean is 1498.78, and with a p-Value of 0.06, higher than the common significance level of 0.05, there is not sufficient evident to support rejecting the null hypothesis. Additionally, when looking at each individual lot, we can see that lot 1 and 2 have roughly the same true mean and will p-Values of 1 and 0.61 respectively, we can concur that the null hypothesis cannot be rejected here either. However, lot 3, with a true mean of 1496.14 and a p-Value of 0.04 (which is lower than the common significance of 0.05), indicates to reject the null hypothesis, which is the oppostie of the other lots.

## Deliverable 4
### Study Design: MechaCar vs Competition

1. Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating. Address the following questions in your description:
a) What metric or metrics are you going to test?
b) What is the null hypothesis or alternative hypothesis?
c) What statistical test would you use to test the hypothesis? And why?
d) What data is needed to run the statistical test?