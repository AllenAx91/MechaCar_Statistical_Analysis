# MechaCar_Statistical_Analysis 🚗

## 1. Linear Regression to Predict MPG

* According to summary results, vehicle_length and ground_clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words, the vehicle length and ground clearance have a significant impact on the dependent variable (mpg). 
* The p-value of our linear regression analysis is 5.35 x 10-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.
* With a high r-squared value of 0.72 and a low p-value much smaller than the significance level, this linear model could be used to predict the mpg of MechaCar prototypes effectively. 

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/1_Linear_Regression_to_Predict_MPG.png)

## 2. Summary Statistics on Suspension Coils

The specifications for the MechaCar suspension coils are within the required 100 pounds per square inch based on the summary of the total lot. However, a variance of 62.3 pounds per square inch is still worth looking into by breaking down the batch into various lots. From the lot-wise summary results, it is clear that Lot 3 having a variance of 170.3 pounds per square inch holds most of the defective suspension coils. 

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/2_TotalLot_Summary.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/3_PerLot_Summary.png)

## 3. T-Tests on Suspension Coils

The p-value from the t-test of the total, 0.06, is above our assumed significance level of 0.05. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar. To improve our analysis as done in the summary statics, a lot-wise breakdown is necessary.

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/Test_Total.png)

The p-values from the t-test of Lots 1 and 2 are above our assumed significance level of 0.05. But Lot 3 has a p-value of 0.042 which is less than 0.05.  Therefore, we have sufficient evidence to reject the null hypothesis of Lot 3, and we would state that the means are not statistically similar.

![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/4_TEST_LOT1.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/5_TEST_LOT2.png)
![](https://github.com/AllenAx91/MechaCar_Statistical_Analysis/blob/main/Images/6_TEST_LOT3.png)

## 4. Study Design: MechaCar vs Competition

### 4.1 Metric

Highway fuel efficiency is a metric looked at when purchasing a car. Therefore, a statistical design using highway fuel efficiency as the dependent variable recorded from multiple car brands of the same vehicle class would be an apt study. 

### 4.2 Null Hypothesis (H0): 

The mean highway fuel efficiency of all cars from the same category is equal

### 4.3 Test selection and Data required :

The ANOVA test would be ideal since we are comparing the means across more than two groups. However, we must ensure that we meet the following test assumptions: 

1) The highway fuel efficiency is normally distributed
2) The variance among each group is similar

The data from each car group has to be recorded under the same climatic and topographical conditions to meet the above assumptions.  








