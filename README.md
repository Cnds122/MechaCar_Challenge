# MechaCar_Challenge

## Linear Regression to Predict MPG
![Alt Text](Images/linear_regression.png)
![Alt Text](Images/Summary_mpg.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- Is the slope of the linear model considered to be zero? Why or why not?

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

## Summary Statistics on Suspension Coils

The figures below demostrate statistical values of suspension coils based on all lots and individual lots
![Alt Text](Images/total_summary.png)
![Alt Text](Images/lot_summary.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

The results dictate that the variance when all lots are grouped together is 62 PSI, which meet the specifications required.
When looking at lots individually, lot 1 and lot 2 also meet the requirements with 1 and 7 PSI, respectively. Lot 3 has a variance of 170 PSI which does not meet design specifications.

## T-Tests on Suspension Coils

T-Tests were performed to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

Null Hypothesis: There is no significant difference between the mean PSI of all manufacturing lots and individual lots and population mean of 1500 PSI.

Alternate Hypothesis: There is significant difference between the mean PSI of all manufacturing lots and individual lots and population mean of 1500 PSI

The significance value will be 0.05

Below is the t-test results for all manufacturing lots. The p-value is 0.06. Since the p-value is greater than our 0.05 significance value we fail to reject the null hypothesis.
![Alt Text](Images/t_test.png)

Below are the t-test results for individual lots. The p-value for lot 1, 2, and 3 are 1, 0.6, and 0.04, respectively.

Since the p-value for lot 1 and 2 are greater than our 0.05 significance value we fail to reject the null hypothesis.

For lot 3, the p-value is less than our 0.05 significance value therefore we reject the null hypothesis.
![Alt Text](Images/lot1.png)
![Alt Text](Images/lot2.png)
![Alt Text](Images/lot3.png)

# Study Design: MechaCar vs Competition
- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?
