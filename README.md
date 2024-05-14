# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
developed by: NITHIYANANDAN N
Register number:212222230099
import pandas as pd
df = pd.read_csv('letter-recognition (1).csv')
print(df.head())
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![image](https://github.com/NITHIYANANDAN278/Read-from-CSV/assets/121784636/73045344-d9e4-45b7-9056-5fac6c8891bd)




## RESULT:
Thus the python program for reading the csv file content is executed successfully
