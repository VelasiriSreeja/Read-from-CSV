# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:Start the python.
### Step 2:Import pandas.
### Step 3:Mention the CSV file which is to be read.
### Step 4:Read the contents of the CSV file using df.read function.
### Step 5:End the program.

## PROGRAM:
```
developed by:v.sreeja
register number:22004463

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car.csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO@ for the corresponding weight and volume",predictedCO2)

```
## OUTPUT:
![output](Screenshot%20from%202023-01-26%2010-20-29.png)

## RESULT:
Thus a program to read the contents of csv file using the python programming language.
