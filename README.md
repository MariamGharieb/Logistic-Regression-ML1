# Logistic-Regression-ML1
A certain car company is planning to manufacture and launch a new car. So, the
company’s consultants need to study the factors which the pricing of cars
depends on. Based on various market surveys, the consultants gathered a
dataset of different types of cars across the market. They would like to know
which of the car features are significant in predicting the price of a car.
In addition, they would like to predict whether customers will be interested in
purchasing the new car. That’s why they collected a few records of some of the
company’s previous customers who either purchased a new car from the
company as an upgrade or didn’t purchase a new car.
You are required to build a linear regression model and a logistic regression
model for this

the dataset “customer_data.csv” contains 400 records
representing some of the company’s previous customers. The customer
data is composed of the customer’s age and salary. The final column (i.e.,
the target) is a boolean value (0 if the customer didn’t purchase a new car
and 1 if he/she purchased a new car).

Requirement:
a- Load the “customer_data.csv” dataset.
b- Split the dataset into training and testing sets.
c- Implement logistic regression from scratch using gradient descent
to optimize the parameters of the hypothesis function. Use the 2
features (age & salary) as input and the output to be predicted is
“purchased”.
d- Use the optimized hypothesis function to make predictions on new
data.
e- Calculate the accuracy of the final (trained) model on the test set.
