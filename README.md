# MechaCar_Challenge

# Overview

## Linear Regression to Predict MPG
1. Vechicle length and vechicle ground clearance are two of the variables that provide can provide a non-random amounts of variance to the model. This means that the vehicle length and ground clearnace do have a significant effect on the miles per gallon on the MechaCar prototype. Vehicle weight, spoiler angle, and all wheel drive have p-values so this can tell us that there is a random amouunt of variance with dataset.
2. The slope of the model is considered to not be zero. This is because we rejected our null hypothesis since the p-value was very small to the compared to the significance level.
3. This model does predict pmg of MechaCar prototypes effectively because the r-squared value was 0.7149 which means that 71% of the predictions can be determined by this model.

## Summary Statistics on Suspension Coils
1. The current manufacturing data for all manufacturing lots does fall below 100 PSI. The value is 62.29 PSI. Looking at the lots seperately, Lot 1 and 2 fall within the requirement with variances of 0.98 and 7.47. Lot 3 shows more variance.

## T-Tests on Suspension Coils
1. Lot 3 seems to be a different issue. Lot 3 needs to be checked for system fails and suspension coils as they do not meet quality criteria. The sample mean for this lot was 1496.14 with a p-value of 0.04 which was lower than the significant level of 0.05. This means that we need to reject the null hypothesis because they are not statistically different.

## Study Design: MechaCar vs Competition
1. Metrics that I would test would be the vehicle weight with the safety rating because it would be a competitive advantage.
2. The null hypothesis would be H0 : PH = 0.1(High)Ha : PH ≠ 0.1(High)
3. I would use the two-tailied hypothesis because I can calculate the significance level to prove their is an additional safety feature or if it would not make a difference. 
5. The data that would be needed is the data of the weight of the vehicle and accidents.
