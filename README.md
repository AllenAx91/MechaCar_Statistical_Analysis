# MechaCar_Statistical_Analysis 🚗

## Linear Regression to Predict MPG

* According to summary results, vehicle_length and ground_clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words, the vehicle length and ground clearance have a significant impact on the dependant variable (mpg). 
* The p-value of our linear regression analysis is 5.35 x 10-11, is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.
* With a high r-squared value of 0.72 and low p-value much smaller than the significace level, this linear model could be used predict mpg of MechaCar prototypes effectively. 

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/1_Linear_Regression_to_Predict_MPG.png)

## Summary Statistics on Suspension Coils

Cosidering the summary of the total lot, the design specifications for the MechaCar suspension coils is within the required 100 pounds per square inch. However, a variance of 62.3 pounds per square inch is still worth looking into by breaking down the batch into various lots. From the lot-wise summary results, it is clear that Lot 3 having a variance of 170.3 pounds per square inch has a lot of defective suspension coils. 

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/2_TotalLot_Summary.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/3_PerLot_Summary.png)

## T-Tests on Suspension Coils

The p-value from the t-test of the total, 0.06, is above our assumed significance level of 0.05. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar. To improve our analysis as done in the summary statics, a lot-wise breakdown is necessary.

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/Test_Total.png)

The p-values from the t-test of Lots 1 and 2 is above our assumed significance level of 0.05. But Lot 3 has a p-value of 0.042 which is less that 0.05.  Therefore, we have sufficient evidence to reject the null hypothesis of Lot 3, and we would state that the means are not statistically similar.

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/4_TEST_LOT1.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/5_TEST_LOT2.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/6_TEST_LOT3.png)

## Study Design: MechaCar vs Competition
