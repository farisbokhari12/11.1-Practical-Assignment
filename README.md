# Report on Used Cars Prices Influences

# Introduction

This analysis utilized a Linear Regression and Random Forest Regression model to figure out the factors that are most likely to influence the prices of used cars. The linear regression model was used in this analysis to understand the impact of individual features on car prices. While, the use of the random forest model provides a way to gather more information about non-linear relationships and potential interactions between different features. The goal being to provide actionable insights to help used car dealers fine tune their inventory to maximize on profits and choosing vehicles that would benefit the dealership.

Model Performance
The model performance was measured by using the MSE and RMSE to understand how much variability the predictions of the models differed from the original values of the dataset.

Linear Regression

- Best MSE on Validation Set: 128,198,326.81
- Best MSE on Test Set: 132,150,263.03
- Best RMSE on Test Set: 11,495.66
- Cross-Validation RMSE: 11,978.48
- Cross-Validation MSE: 143,483,946.03

Random Forest Regression

- Best MSE on Validation Set: 34,564,020.51
- Best MSE on Test Set: 37,592,985.97
- Best RMSE on Test Set: 6,152.04
- Cross-Validation RMSE: 8,265.97
- Cross-Validation MSE: 68,326,238.19

From these results, the Random Forest model outperforms the Linear Regression model, showing lower MSE and RMSE values, both on the test set and in cross-validation.

# Key Findings from Linear Regression Model
The top factors influencing car prices based on the Linear Regression model are as follows:

Positive Influences on Price:
- Fuel Type (Diesel): Cars with diesel engines have significantly higher prices.
- Age: The newer the car the higher the price tends to be
- 8 Cylinder Vehicles: These vehichles were valued at higher prices compared to other vehicle types.
- 4WD Vehicles: Cars with 4WD were valued at higher prices.
- Condition (Excellent): Cars in excellent condition are priced higher.

Negative Influences on Price:
- Manufacturer (Hyundai): Cars from Hyundai tend to have lower prices.
- FWD Vehicles: Front-wheel-drive cars generally trended to having lower prices.
- Gasoline Powered Cars: Gasoline engines generally had lower prices.
- Sedan Vehicles: Sedan body type vehicles had lower prices.
- 8 Cylinder Vehicles: These vehichles were valued at lower prices compared to other vehicle types.

# Key Findings from Random Forest Model
The top factors influencing car prices based on the Random Forest model are as follows:

Positive Influences on Price:

- Cylinders (8 cylinders): Similar to the linear model, cars with 8-cylinder engines are valued more.
- Body Type (Truck): Trucks are priced higher.
- 4WD Vehicles: Cars with 4WD were valued at higher prices.
- Fuel Type (Diesel): Diesel cars have higher prices.
- Manufacturer (Ford): Cars from Ford have higher prices.

Negative Influences on Price:

- Manufacturer (Hyundai): Hyundai cars tend to have lower prices.
- State (OH): Cars sold in Ohio are priced lower.
- Cylinders (6 cylinders): Cars with 6-cylinder engines are priced lower.
- Paint Color (Grey, Blue): Cars with these colors tend to be priced lower.
- Body Type (Wagon, Hatchback): These body types tend to have lower prices.

# Recommendations
Based on the analysis, it is recommended to look into the following strategies to fine tune inventory:

Inventory Focus:
- Prioritize acquiring diesel cars, trucks, and 4WD vehicles.
- Ensure a good mix of cars from manufacturers like Ford and models with 8-cylinder engines.
- Condition and Age:
- Maintain a high standard of vehicle condition, particularly focusing on newer cars and those in excellent condition.

Avoid Low-Value Segments:
- Be cautious with inventory from manufacturers like Hyundai.
- Minimize the stock of sedans, cars with 4-cylinder engines, and vehicles with gasoline engines.

Regional Considerations:
- Be aware of regional price differences; for example, avoid overstocking in regions where prices are typically lower, such as Ohio.

