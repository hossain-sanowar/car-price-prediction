# car-price-prediction
## <a>Car Price Prediction<A>

**Problem Statement** <br>
Geely Auto, a Chinese automaker, intends to join the U.S. market by establishing a manufacturing facility there and producing automobiles locally to compete with U.S. and European automakers.

They have hired an automotive consulting firm in order to "understand the elements that influence the price of automobiles." Specifically, they want to comprehend the elements influencing the price of automobiles on the American market, since they may vary significantly from those on the Chinese market. The business want to know:

- How well do these factors explain the pricing of a car?

Based on several market studies, the consulting business has amassed a sizable dataset on various kinds of automobiles available on the American market

**Business Goal**<br>
To create the model using the supplied independent variables, automobile prices are necessary. It will be utilized by management to comprehend the actual relationship between pricing and independent factors. Consequently, they may change the design of the automobiles, the business strategy, etc. in order to achieve particular pricing levels. Moreover, the model would aid management in comprehending the price dynamics of a new market.

**To develop the model, below stages are followed :**<br>

1) Importing libraries <br>
2) Gathering dataset<br>
3) Data Understanding <br>
4) Data handling <br>
5) Data visulaisation<br>
6) Data preparation<br>
7) Splitting the Data and feature scaling <br>
8) Building a linear regression model  <br>
9) Residual analysis of the train data <br>
10) Select the Final Model <br>
11) Model Evaluation <br>
12) Conclusions <br>

## Conclusions

The model is used to draw conclusions.<br>

1.) R-squared and Adjusted R-squared (fitness) are 0.875% and 0.870%, respectively, accounting for 87% of the variance. <br>
2.) F-statistics and Prob(F-statistics) (overall model fit) are 192.0 and 6.44e-60 (almost 0.0) - Model fit is substantial and 87% of variation explained is not due to chance.
<br>
3.) p-values - p-values for all coefficients seem to be less than the 0.05 significance threshold. This suggests that every predictor is statistically significant. <br>

Consequently, we assert that the model will be a valuable tool for management to comprehend the price dynamics of a new market.

The following factors are crucial in estimating an automobile's price:

- Horsepower 
- wheelbase
- carbody (hatchback)
- carbody (wagon)
- Luxury cars (Cars that are very expensive or high-end)

We can see that the equation of our best fitted line is:

$ Price$ <br> 
$= 0.7081 \times  horsepower + 0.3093 \times  wheelbase + 0.2436 \times class luxury - 0.0441 \times carbody hatchback - 0.0456 \times carbody wagon -0.0715$

