# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Display the result.


## PROGRAM:
```
'''
Developed by: sai vivek.R
Register Number:23003676
'''
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:

![Screenshot 2023-12-29 000752](https://github.com/RAGALASAIVIVEK/Read-from-CSV/assets/144979718/59a35572-2fee-4ff4-a171-49bded631bf5)


## RESULT:
thus python program for reading content from CSV file is successful.
