# Class 13 - Linear Regressions
----------------------------------------------------------------------------------
## Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?
----------------------------------------------------------------------------------
Regression searches for relationships among variables. For example, you can observe several employees of some company and try to understand how their salaries depend on their features, such as experience, education level, role, city of employment, and so on.

This is a regression problem where data related to each employee represents one observation. The presumption is that the experience, education, role, and city are the independent features, while the salary depends on them.


## Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions
----------------------------------------------------------------------------------
The process of implementing a linear regression model using Python’s Scikit Learn library is as follows:

1. Import the required libraries.
```
from sklearn.linear_model import LinearRegression
sklearn.linear_model.LinearRegression()
```

2. Create a numpy array of data
```
x = np.array([6, 16, 26, 36, 46, 56]).reshape((-1, 1))
y = np.array([4, 23, 10, 12, 22, 35])
```
3. Create a linear regression model.
```
model = LinearRegression().fit(x, y)
```
4. Obtain the coefficient of determination by calling the model with the score() function, then print the coefficientز
```
r_sq = model.score(x, y)
print('coefficient of determination:', r_sq)
```

## What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?
----------------------------------------------------------------------------------
The purpose of splitting the dataset into train and test sets is to evaluate the performance of the model on unseen data. The model is trained on the training set and then evaluated on the test set.