# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset.
- The p-value of linear regression analysis is 5.35 x 10^(-11) which is much smaller than the assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis which means the slope of the linear model is not zero
- The r-squared value, in this case, is 0.71, meaning roughly 71% of the variability of fuel efficiency (mpg) is explained using this linear model. However, there is a lack of significant variables which means it fails to generalize and predict future data. There are probably other factors out not captured in this dataset that contribute to the variability of mpg. 

## Summary Statistics on Suspension Coils

A mean of 1498.78 and a median of 1500 were observed for all the manufacturing lots as a whole. The variance is 62.29 which doesn't exceed 100 pounds per square inch. 

For each lot, lot 1 and lot 2's variance both doesn't exceed the design specification either and have very similar mean and median. However, lot 3's variance of 170.29 exceeds the manufacturers' specification of 100 pounds per square inch. 

## T-Tests on Suspension Coils

- The p-value across all manufacturing lots is 0.06, higher than the significance level of 0.05. Therefore, there is no statistical difference between mean PSI across all manufacturing lots and the population's mean of 1,500 pounds per square inch.

- For Lot 1 and Lot 2, the p-values are 1 and 0.61 respectfully, above the significance level (0.05). Therefore, we don't have sufficient evidence to reject the null hypothesis. This means that there is no statistical difference between the Lot1 and Lot2 means and the population mean of 1500. 

- The p-value for Lot 3 is 0.04, less than the significance level. this means that there is a statistical difference between Lot 3 mean and the population's mean. 

## Study Design: MechaCar vs Competition

### Metics Tested

To see how the MechaCar performs against the competition. Various metrics of interest could be tested such as highway fuel efficiency, horsepower and safety rating. In this study, we are interested in fuel efficiency, and safety rating. 

### Hypotheses example

Null Hypothesis: MechaCars have no difference in Safety rating compares to its competitors, and have no difference in fuel efficiency to its competitors. The true mean difference is equal to zero.

Alternative Hypothesis: MechaCars have a difference in Safety rating compares to its competitors, and have a difference in fuel efficiency. The true mean difference is not equal to zero.

### Dataset Required

Numerical data for fuel efficiency and safety rating from MechaCar and its competitors are needed. 

### Statistical test

In this study, we will use two sample pair t-test to compare the means from different populations. Afterward, we will determine which means are greater than or less than the other.

