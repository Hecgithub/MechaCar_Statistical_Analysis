# MechaCar_Statistical_Analysis

## Linear Regression Predict MPG
•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The vehicle length and ground clearance provided non-random amounts of variance to the mpg values in the dataset.

•	Is the slope of the linear model considered to be zero? Why or why not?

Given the P-value of 5.35e-11 the slope of the linear model can not be considered zero. The null hypothesis must be rejected, and there is a correlation between the variables and the MPG. 

•	Does this linear model predict MPG of MechaCar prototypes effectively? Why or why not?

The linear model indicates a 71% accuracy, there is a strong probability that the model predicts mpg of the MechaCar prototype effectively. 

 ![image](https://user-images.githubusercontent.com/110510718/205425497-56f1d740-043b-4c37-adbd-b49fd633606c.png)
![image](https://user-images.githubusercontent.com/110510718/205425503-b0652cf1-8dcd-496e-adbc-896ef3d63030.png)
![image](https://user-images.githubusercontent.com/110510718/205425506-9a3cd4df-48b5-4a53-9d87-0d0c473f7d27.png)


## Summary Statistics on Suspension Coils
•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The overall summary data illustrates that the manufacturer meets the specifications, although Lot3 is outside the acceptable threshold of 100 as it is at 170.28.  
 
![image](https://user-images.githubusercontent.com/110510718/205425512-8c7c07c4-3fd1-46ab-84f2-9eebe66012fa.png)

 ![image](https://user-images.githubusercontent.com/110510718/205425520-5d0c361d-ce50-47bb-aee5-7a8f57cb000f.png)



## T-Tests on Suspension Coils 

 ![image](https://user-images.githubusercontent.com/110510718/205425564-3c031369-635e-4742-b013-036d1fd40a80.png)

 
•	The T-test results for all manufacturing lots for suspension coils demonstrate no statistical difference from the population mean. Furthermore, the p-value is 0.06028, so the null hypothesis cannot be rejected.  


![image](https://user-images.githubusercontent.com/110510718/205425604-de66a416-900a-49e2-97a4-a8ee5af19fe2.png)

 
•	Lot 1 has a sample mean of 1500 and a P-value of 1, so we cannot reject the null hypothesis.

•	Lot 2 has a sample mean of 1500.02 and a P-value of 0.6072, so we cannot reject the null hypothesis. 

•	Lot 3 has a sample mean of 1496.14 and a P-value of 0.04168, so we do reject the null hypothesis that this sample mean and the presumed population mean are not statistically different. 

•	In summary, Lot 3 production cycle may have an issue and should not be used.  

## Study Design: MechaCar vs. Competition

To conduct a statistical study that can quantify how MechaCar performs against the competition, we must consider consumer interests such as utility, affordability, and efficiency. These are three factors that can be measured and tested in the study. The following process will map out the study:

•	What metric or metrics are going to be tested? 
Utility, affordability, and efficiency. 

•	What is the null hypothesis or alternative hypothesis?

H0: There is NO statistical significant difference on defined metrics between MechaCar and competition.

Ha: The is statistical significant difference on defined metrics between MecharCar and competition.

•	What statistical test would you use to test the hypothesis? And why? What data is needed to run the statistical test?

We are collecting utility, affordability, and efficiency data for all MechaCar competitors from the Sedan vehicle class to perform the analysis. All the competitor data is grouped together for our analysis.

Then we would perform t-tests on each of the metrics for MechaCar against the same metric from the collective competition data.
If the p-value for each t-test is less than 0.05, we will reject our NULL hypothesis.

