## Linear Regression in Machine Learning
Linear regression is one of the easiest and most popular Machine Learning algorithms. It is a statistical method that is used for predictive analysis. Linear regression makes predictions for continuous/real or numeric variables such as sales, salary, age, product price, etc.

Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (y) variables, hence called as linear regression. Since linear regression shows the linear relationship, which means it finds how the value of the dependent variable is changing according to the value of the independent variable.


## Linear Regression with Python

Your neighbor is a real estate agent and wants some help predicting housing prices for regions in the USA. It would be great if you could somehow create a model for her that allows her to put in a few features of a house and returns back an estimate of what the house would sell for.

She has asked you if you could help her out with your new data science skills. You say yes, and decide that Linear Regression might be a good path to solve this problem!

Your neighbor then gives you some information about a bunch of houses in regions of the United States,it is all in the data set: USA_Housing.csv.

The data contains the following columns:

    'Avg. Area Income': Avg. Income of residents of the city house is located in.
    'Avg. Area House Age': Avg Age of Houses in same city
    'Avg. Area Number of Rooms': Avg Number of Rooms for Houses in same city
    'Avg. Area Number of Bedrooms': Avg Number of Bedrooms for Houses in same city
    'Area Population': Population of city house is located in
    'Price': Price that the house sold at
    'Address': Address for the house



### Regression Evaluation Metrics
    Here are three common evaluation metrics for regression problems:

### Mean Absolute Error;
    (MAE) is the mean of the absolute value of the errors:

### Mean Squared Error:
    (MSE) is the mean of the squared errors:
 
### Root Mean Squared Error:
    (RMSE) is the square root of the mean of the squared errors:

MAE is the easiest to understand, because it's the average error.

MSE is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world.

RMSE is even more popular than MSE, because RMSE is interpretable in the "y" units.

#### All of these are loss functions, because we want to minimize them.



