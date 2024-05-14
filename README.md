# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
Developed by: santhosh kumar B

Register number: 212223230193


import pandas as pd

from sklearn import linear_model

data=pd.read_csv("C:/Users/admin/Downloads/car (1).csv")

x=data[['Weight','Volume']]

y=data[['CO2']]

regr=linear_model.LinearRegression()

regr.fit(x,y)

print('Coefficients:',regr.coef_)

print('Intercept:',regr.intercept_)

predictCO2=regr.predict([[3300,1300]])

print('predicted CO2 for the corresponding weight and volume',predictCO2)






```
## Output:

![image](https://github.com/Santhoshstudent/Multivariate-Linear-Regression/assets/145446853/f88e0747-bd03-46a5-aff3-efd1eb8eff4b)


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
