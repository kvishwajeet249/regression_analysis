# regression_analysis

In this study, we are conducting a Regression Analysis on car sales data to examine the factors that influence the price of cars. The variables considered are:

Brand
Mileage
Engine volume
Year of production
To include the brand information in the model, we have utilized dummy variables. We first checked for linearity between the independent variables and the dependent variable (car price) using scatter plots.

As part of data preprocessing, we applied log transformations to one or more variables to improve the model's performance.

The analysis was conducted in two stages:

Individual Variable Regressions:
We performed separate linear regression analyses using each individual variable (mileage, engine volume, and year) as the predictor. These individual regressions helped us understand the impact of each variable on car prices independently.

Multiple Variable Regression:
Next, we combined all the variables (mileage, engine volume, year, and brand) in the regression model to investigate their joint effect on car prices. By introducing brand information with the aid of dummy variables, we included it as a predictor in the model.

The results from the multiple variable regression indicate that all the variables in the model, including brand, are statistically significant. The model achieved an R-squared value of 80%, signifying that it can explain 80% of the total variability in car prices. This high R-squared value demonstrates that the model has a very high explanatory power, which means it can effectively capture and explain the relationships between the predictors (mileage, engine volume, year, and brand) and the dependent variable (car price).

Overall, the inclusion of brand information using dummy variables has significantly improved the model's ability to explain the variability in car prices. This finding suggests that brand plays a substantial role in determining the price of cars in our regression analysis.


