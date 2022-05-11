## Advanced_Regression Assignment
### Problem Statetment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below
 their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict
 the actual value of the prospective properties and decide whether to invest in them or not.

#### The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

### Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the
 prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model
 will be a good way for management to understand the pricing dynamics of a new market.

### Steps
- Import library
- Read Data
- Data understanding
- Data Cleaning
- Remove Outlier
- EDA
- Data Preparation
- RFE
- Lasso regression
- Ridge regression
- Linearity Check
- Conclusion
- Experiment for Subjective Questions

## Conclusion
### Both model Ridge and Lasso gives very good results
### we can see that the r2_scores are almost same for both the model but as we know lasso will penalize more and help in feature elimination also, so my go to model will be that only. 
Our top 5 features are -
- PoolArea
- Neighborhood_SWISU
- KitchenQual
- BstmCond
- KitchenAbvGr


## Technologies Used
- numpy 1.20.3
- pandas 1.3.4
- matplotlib 3.4.3
- seaborn 0.11.2
- scikit-learn 0.24.2
- statsmodels 0.12.2


