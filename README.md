# MechaCar_Statistical_Analysis
## Overview of Project
### Purpose:
Try to predict the mpg for prototypes by MechaCar and conduct statistical PSI coil suspension summaries from manufacturers. 


### Linear Regression to Predict MPG
Using linear regression model, the r-square = 0.71 represents a strong link between the variables and MPG. Eliminating the null hypothesis (Dependant variables do not affect the changes in the MPG with the slope is zero) after concluding that the slope is not zero and dependant variables do contribute to the change in MPG due to the p-value being = 5.35e-11.The PRr(>|t|) of  ground clearance (PRr(>|t|)=5.21e-8) and vehicle length (PRr(>|t|)=2.60e-12 do not provide randomness into the variance of the linear model. Because  (PRr(>|t|)=5.08e-8), this justifies a the amount of variablitliy in mpg when all independent variables are zero. Since there are not many important variables, the data can reduce the means to foresee and simplify potential regression and dataset models but can visualize decent performance in the present dataset.





## Summary Statistics on Suspension Coils
To assess the uniformity of the manufacturing process across different lots, suspension coils were tested by calculating statistics summaries for the individual lot numbers and total of the suspension coils. 
Below are the summaries of the suspension coils:

Each lot individually:


![statistis on suspension coils](https://user-images.githubusercontent.com/98041751/172154964-d45af4b8-8cf9-4e82-be25-47309c830e5f.png)

Summary statistics for each lot individually:

![statistis on suspension coils 2](https://user-images.githubusercontent.com/98041751/172155042-26f63764-a21c-4ea6-bad2-2f2f502d22d6.png)


100 PSI variance cannot be exceeded by design specifications, and based on the images above, the combines psi is var=62.3, which does meet the requirements. However lot 3 does has car=170 PSI and is an outlier. 



### T-Tests on Suspension Coils
T-Test Evaluating Mean PSI population = 1500  vs. Manufacturing Lots:

H0: There is no statistical difference between the observed sample mean and its presumed population mean.
HA: There is statistical difference between the observed sample mean and its presumed population mean.
We calculated a p-value = 0.06, therefore we do not reject the null hypothesis and conclude that there is no statistical difference between the obsvered sample mean and its presumed population mean. If the p-value is less than or equal to 0.05, then can reject the null hypothesis because we are within 95% of our significance level.


![T-tests](https://user-images.githubusercontent.com/98041751/172155121-d822e8d4-2073-4acc-b732-6e00d497e1ba.png)


T-Test Comparing Each Manufacturing Lot vs. Mean PSI population = 1500:

H0: There is no statistical difference between Lot 1 sample mean and its population mean.
HA: There is a statistical difference between Lot 1 sample mean and its population mean
The null hypothesis is not rejected because the P-value of lot 1 is 1. 



![PSI population equals 150](https://user-images.githubusercontent.com/98041751/172155164-c4f54d20-0a42-4c3a-9597-7e7d97d85f5b.png)

H0: There is no statistical difference between Lot 2 sample mean and its population mean.
HA: There is a statistical difference between Lot 2 sample mean and its population mean
The null hypothesis is not rejected because the P-value of lot 2 is 0.6.

![PSI population equals 150 2](https://user-images.githubusercontent.com/98041751/172155213-ed67fada-04be-45c2-8ea7-41453d3680e9.png)


H0: There is no statistical difference between Lot 3 sample mean and its population mean.
HA: There is a statistical difference between Lot 3 sample mean and its population mean
Because Lot 3’s  p-value = 0.04, we must reject the null hypothesis since there is a statistical difference between the mean of its observed sample and its presumed population. 


![PSI population equals 150 3](https://user-images.githubusercontent.com/98041751/172155228-1662e11f-8c56-4edf-9c5d-0d19aafc70c3.png)

### Conclusion: MechaCar vs Others
To compare statistical data from MechaCar and other manufacturers, we can use ANOVA for the analysis, which would compare the averages of multiple competitors’ vehicles to MechaCars. Independent variables can be tested in a 1-way or be repeated with a multitude of other variables why a 2 way test can be used for 2 different variables which would execute the following hypothesis:

H0: There is no statistical difference between observation sample mean 1 and observation sample mean 2 (µ1 ≠ µ2 ≠ ... ≠ µn).
HA: There is statistical difference between observation sample mean 1 and observation sample mean 2 (µ1 = µ2 = ... = µn).
The p-value of the test would show statistical difference or no statistical difference between the 2 different variables being observed.
