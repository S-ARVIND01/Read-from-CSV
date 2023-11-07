# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.


## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```python
import pandas as pd
f = pd.read_csv("nba.csv")
print(f.head(10))
print(f.tail())
print("Number of Rows :",len(f.axes[0]))
print("Number of Columns :",len(f.axes[1]))
```
## OUTPUT:
![Screenshot 2023-11-07 095612](https://github.com/S-ARVIND01/Read-from-CSV/assets/118707337/093bbfbf-07aa-4f7d-a4d8-4451557b43d9)

## RESULT:
Hence the program is executed successfully!
