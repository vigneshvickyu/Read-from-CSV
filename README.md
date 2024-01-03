# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
## Step 1:
Import pandas as pd
## Step 2:
Read the csv file using read_csv method.
## Step 3:
Use head and tail method to get the required contents from the file.
## Step 4:
Use len() method to get the number of rows and columns.
## Step 5:
Print the output


## PROGRAM:
\*
# Program to read contents from a csv file
# Developed by: V. Yogesh
# Register no: 212223230250
\*
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows: ",len(df.axes[0]))
print("Number of columns: ",len(df.axes[1])

## OUTPUT:

![image](https://github.com/vigneshvickyu/Read-from-CSV/assets/151948835/766f2eb0-1714-44e5-a61a-e4acebbb3d26)


## RESULT:
Thus a python program is written to read the contents of a csv file
