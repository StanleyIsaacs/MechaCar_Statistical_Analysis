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

## Summary Statistics of Supension Coils
*MechaCar suspension coils specifications say the variance of the suspension coils cannnot exceed 100 pounds per square inch.
*The design specifications are universal for all manufacturing lots with a global variance of 62.3 psi.
*Lot 1 and Lot 2 are specifications with respective variances of 0.98 and 7.5 psi. The Lot 3 is out of specifications with a variance of 170.3 psi.

<img width="333" alt="AllLots" src="https://user-images.githubusercontent.com/82114481/132247684-4ed20a1d-9726-4d94-bda8-e8e5a22098b7.png">

<img width="490" alt="SpecificLots" src="https://user-images.githubusercontent.com/82114481/132247692-7a93f365-5790-4548-bdae-1c8bc193d90f.png">


