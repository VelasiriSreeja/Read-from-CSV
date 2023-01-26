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
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))


```
## OUTPUT:
![output](Screenshot%20from%202023-01-26%2015-04-32.png)



## RESULT:
Thus a program to read the contents of csv file using the python programming language.
