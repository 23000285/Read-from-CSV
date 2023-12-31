# Read-from-CSV
## AIM:
To write a Python program to read read contents from csv file

## ALGORITHM:
### Step 1:
Import and load
   
### Step 2:
Peek at data 

### Step 3:
Check dimensions

### Step 4:
Print the number of rows and columns in the DataFrame.

## PROGRAM:
```
# Program to read read contents from csv file 
# Developed by : VENKATANATHAN P R
# Register Number : 23000285 
 
import pandas as pd 
df=pd.read_csv('nba.csv') 
print(df.head(10)) 
print(df.tail(5)) 
print("Number of rows: ",len(df.axes[0])) 
print("Number of columns: ",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/23000285/Read-from-CSV/assets/138970859/2335880d-3ae3-4e9c-81b2-9637ef46f091)

## RESULT:
Thus the python program to read read contents from csv file is executed.
