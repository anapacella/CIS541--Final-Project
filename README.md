# CIS541 Final Project

## Predicting Sales According to Wine Reviews

### Data

The dataset was extrated from Kaggle (public to everyone). The Wine Testing Data has a little bit more than 100k rows and 10 variables such as description of wine, designation, its rating, price, region, amongst others. For the purpopse of this study, I only used the following: country, reviews (points), price and variety.

### Purpose of study

The main idea with this study was to better know the product and see what types of wines were getting the most points, or better reviews. Also, to see what factors were driving the wine prices and finally, to spot the differences between the best sellers: Chardonnay and Pinot Noir. 

### Procedure

To analyze the data, some visuals were created with ggplot to better see where the data points were at.

After calculating averages of prices and points for both, Chardonnay and Pinot Noir, I continued with some test statistics and regression analysis and concluded that the best model for predicting price is nonlinear, since the RMSE value was lower.
