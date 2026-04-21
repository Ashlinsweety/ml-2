# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
 1.Import required libraries: NumPy for data handling, Matplotlib for plotting, and LinearRegression from sklearn.

2.Define input feature array X (hours studied) and output array Y (marks scored), and reshape X into a 2D array.

3.Initialize the Linear Regression model using LinearRegression().

4.Fit the model using training data (model.fit(X, Y)) to learn slope and intercept.

5.Take user input (hours studied), use model.predict() to estimate marks, and display the result.

6.Plot the actual data points using scatter plot and draw the regression line using predicted values.

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
X=np.array([1,2,3,4,5]).reshape(-1,1)
Y=np.arrary([35,50,65,70,85])
model=LinearRegression()
model.fit(X,Y)
m=model.coef_[0]
b=model.intercept_
print("Slope(m):",m)
print("Intercept(b):",b)
x_input=float(input("Enter hours studied:"))
predicted_marks=model.predict([[x_input]])
print("Predicted Marks:",predicted_marks[0])
Y_pred=model.predict(X)
plt.scatter(X,Y,label="Actual Data")
plt.plot(X,Y_pred,label="Regression Line")
plt.xlabel("Hours Studied")
plt.ylabel("Marks Scored")
plt.legend()
plt.show()
Developed by:R.Ashlin Sweety
RegisterNumber:212225040031
*/
```

## Output:
<img width="822" height="682" alt="WhatsApp Image 2026-04-21 at 9 38 35 AM" src="https://github.com/user-attachments/assets/ed78b88a-4f1d-4ab6-b70e-fec51bafc19c" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.











































































































































































































...
