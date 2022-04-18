# MechaCarChallenge

# Summary Linear Regression
1) Vehicle weight, spoiler angle, and AWD all contributed to a non-random amount of variation. The variables with the most random variance were ground clearance and vehicle length.
2) The p-value is less than 0.05, indicating that our slope is not zero.
3) Our R-squared value is 71%, which means that the model correctly predicts mpg values 71% of the time. Other factors that are likely not captured in the dataset contribute to the mpg variability of the MechaCar prototypes.

# Summary Suspensions Coils

The MechaCar suspension coils must have a variance of no more than 100 pounds per square inch, according to the design specifications. Is the current manufacturing data compliant with this design specification for all manufacturing lots as a whole and for each lot separately? If so, why or why not?

Lot 1 and Lot 2 both fall within the design parameters and have nearly identical mean and median values. Lot 3 has the most variation and exceeds the manufacturer's specifications.

# Deliverable 4: Study Design: MechaCar vs Competition
When deciding on a vehicle to purchase, consumers consider a variety of factors. However, in a world where ridesharing is becoming more common and it's easy and cheap to get around in other people's cars, customers looking to buy a car want more than just a mode of transportation. They will be looking to purchase a car that will provide them with a cost-effective way to transport themselves and their belongings on a regular and dependable basis.
To narrow our test, we should compare the carrying capacity of MechaCar to that of various competitors' vehicles in cubic inches.
H0: The average carrying capacity of MechaCar prototypes is comparable to that of competitors' vehicles in the same vehicle class. Ha: The average carrying capacity of MechaCar prototypes is statistically higher or lower than that of competitors

Two-sample t-tests are the best statistical tests for this.
We'd need cubic space data from the carrying compartments of all MechaCar prototypes, as well as all major competitor vehicles.
