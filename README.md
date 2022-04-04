# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
***Deliverable 1***

![D1_MechaCar](https://user-images.githubusercontent.com/92958939/161637701-5711626d-8abb-453b-95e0-35cc6f3f0b59.png)

•	Vehicle_length and ground_clearance provided a non-random amount of variance to the mpg values in the dataset.
•	The slope of the linear model is not considered to be a zero due to the Multiple R-Squared: 0.72 and Adjusted R-Squared: 0.68
•	This linear model does not predict mpg of MechaCar prototypes effectively due to not enough variables/coefficients included in the analysis. 


## Summary Statistics on Suspension Coils
***Deliverable 2***

![D2_lot_summary](https://user-images.githubusercontent.com/92958939/161637755-8585b492-dc78-4d5f-9e0a-555768f5e3f6.png)
![D2_total_summary](https://user-images.githubusercontent.com/92958939/161637765-7d5f9685-ff61-491c-b705-8b36dba4a8c6.png)

The total_summary Variance is 62.29. That information shows that the current manufacturing data meets the design specification because the variance of the suspension coils does not exceed 100 pounds per square inch. Unfortunately Lot3 under lot_summary Variance is 170.29. Due to that variance exceeding 100 it does not meet the design specifications for all manufacturing lots. Lot1 and Lot2 do meet specification with their variance being 0.98 and 7.47 respectfully. 


## T-Tests on Suspension Coils
***Deliverable 3***

![D3_t test](https://user-images.githubusercontent.com/92958939/161637806-9027a09e-244f-4108-a2a4-81026f4e1455.png)

Due to the p-value being 0.06, we do not have enough evidence to reject the null hypothesis.
Lot1 p-value is 1. Due to it being higher than 0.05 we do not have enough evidence to reject the null hypotheses.
Lot2 p-value is 0.60. Due to it being higher than 0.05 we do not have enough evidence to reject the null hypotheses.
Lot3 p-value is 0.04. Due to it being lower than 0.05 we have enough evidence to reject the null hypotheses.


## Study Design: MechaCar vs Competition
***Deliverable 4***
With today’s high gas prices, I believe a city or highway fuel efficiency statistical study that can quantify how the MechaCar performs against the competition would benefit a lot of people. 
We would need to know if it’s a null hypothesis that shows no difference in the MerchaCar performance against the competition. Or if its an alternative hypotheses that does indeed show if there is a difference between the two.
I would recommend using the ANOVA statistical test to test the hypotheses because it can take more than one variable.
MPG, vehicle_weight, and vehicle_type are the data that is needed to run the statistical test.
