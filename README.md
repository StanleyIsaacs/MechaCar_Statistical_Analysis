# MechaCar_Statistical_Analysis

## Purpose:
### We will be using Rstudio to analyze data set regarding the automotive industry to try and viualize trends.

## Resources:
### We will be using two data sets (Mechacar and Suspension_Coil) and programming exclusively in R code. 

## Linear Regression:
* Based on our results vehicle length and ground clearance and Intercept provide a non-random amount of variance to the linear model of mpg.
*Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model.
### Multi Linear Model:
mpg = 6.27 * vehicle_length + 1.25e-3 * vehicle_weigth + 6.88e-2 * spoiler_angle -3.41 * AWD + 3.55 * ground_clearance - 1.04e+2
### Apprximated:
mpg = 6.27 * vehicle_length - 3.41 * AWD + 3.55 * ground_clearance - 104

* R-square is 0.71 so 71% of the variations in mpg can be explained by changes in the vehicle length, the vehicle weight, the spoiler angle, the drivetrain and the ground clearance.

<img width="517" alt="LinearRegression" src="https://user-images.githubusercontent.com/82114481/132247217-29f1e06e-3043-43b7-ba4c-fbf572715847.png">

