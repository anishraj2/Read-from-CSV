# Read-from-CSV
## AIM:
## To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1: Import pandas module as pd.
### Step 2: Using pd.read_csv() method read the CSV file.
### Step 3: Using df.head() print the first 10 rows of the CSV file.
### Step 4: Using df.tail() print the last 5 of the CSV file.
### Step 5: Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
Developed by: Anish Raj P<br>
Register no:212222230010<br>
import pandas as pd<br>
f=pd.read_csv('/content/nba.csv')<br>
print(f.head(8))<br>
print(f.tail())<br>
print('Number of Rows:',len(f.axes[0]))<br>
print('Number of Column:',len(f.axes[1]))<br>
## OUTPUT:
![OUTPUT](1.png)
## RESULT:
Thus the program is executed successfully.