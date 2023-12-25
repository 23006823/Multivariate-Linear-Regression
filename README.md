# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pands module to solve for multivariate linear regression

### Step2
import pands module to solve for multivariate linear regression

### Step3
open the file cars saved in the drive and get input for weight and volume to find density of CO2


### Step4
print coefficients,intercept and amount

### Step5
end of the program

## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv('/content/drive/My Drive/cars (1).csv')
x=df[['Weight','Volume']]
y=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:
![image](https://github.com/23006823/Multivariate-Linear-Regression/assets/138971409/69e5c3bf-1341-484c-8611-1b42a9121b08)
## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
