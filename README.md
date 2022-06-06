# MechaCar_Analysis

## Linear RegressionFor MPG ##

The Dataset has 6 coefficients and the line helps identify them in the data set.
![Linear Regression](https://user-images.githubusercontent.com/100543143/172079118-f7ce8384-9a42-4a8d-9bd7-ad8988d217f6.png)

In the summary of the linear regression we see the content of the dataset, so the min., median, and max is shown. The coefficients are shown too to determine the content.
![Linear Re  Summary](https://user-images.githubusercontent.com/100543143/172079340-39fe25e9-42a8-43e3-ad31-bd9ff6f8d815.png)


Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The P-value that the summary displayed is compared to alpha = .05, to see if it is significant. Vehicle length and ground clearance variables represent non-random amounts of variance as applied to the mpg values.

Is the slope of the linear model considered to be zero? Why or why not?
The scientific notion has to be converted and once it is converted we see that non of the coefficents are zero.
Coefficients:

-vehicle length: 6.267
-vehicle weight: .001
-spoiler angle: .069
-ground clearance: 3.546
-AWD: -3.411


Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-squared is .7149, and r-squared is the regression error metric to justify the performace and thr r-squared is closer to one than zero.


## Summary of Suspension Coils ##

The summary of the manufacture lot 
<img width="325" alt="Total_summary" src="https://user-images.githubusercontent.com/100543143/172080346-a66b3bfa-c972-499d-8501-d10c9a89b377.png">

<img width="465" alt="Lot_summary" src="https://user-images.githubusercontent.com/100543143/172080403-e0e1ed5d-e848-4b3a-93f6-4c0eda00311a.png">


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

62 < 100 is within the expected design of 100 PSI. Although the variance is 62 the manufactor lots are displaying the specific number, such as Lot1 and Lot2 are within the expectation. Lot1 and Lot2 are 1 and 7.5 which both are under 100, however lot3 is signifcantly higher than the other two, at 170 > 100. As a result of lot3 being high, it does not met the design specifications, lot3 bring the variance number on the total summary display.


### T-Tests on Suspension Coils ### 

Lot 1 T-test:
p-value = 1 > alpha = .05

P-value is greater than alpha, so Lot 1 is not statistically significant from the normal distribution
<img width="556" alt="Lot1" src="https://user-images.githubusercontent.com/100543143/172081176-956021a0-b107-419d-8842-87759731b118.png">

Lot 2 T-Test:
p-value = .6072 > alpha = .05
P-value is greater than alpha, so Lot 1 is not statistically significant from the normal distribution
<img width="557" alt="Lot2" src="https://user-images.githubusercontent.com/100543143/172081282-04ab3b98-ed6c-4cd2-a713-57dd0b0204e2.png">

Lot 3 T-Test:
p-value = .04168 < alpha = .05
Alpha is greater than P-value, which means it is statistically significant from the normal distribution
<img width="556" alt="Lot3" src="https://user-images.githubusercontent.com/100543143/172081397-bf0f9889-7072-4031-880c-03f2a503ab1f.png">


