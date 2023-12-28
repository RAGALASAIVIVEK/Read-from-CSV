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
Developed by:sai vivek.R
RegisterNumber: 23003676
import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
'''
```
## OUTPUT:
![Screenshot 2023-12-29 003248](https://github.com/RAGALASAIVIVEK/Read-from-CSV/assets/144979718/d0d54641-4ee9-43e8-9c22-424edab350ab)


## RESULT:
thus python program for reading content from CSV file is successful.
