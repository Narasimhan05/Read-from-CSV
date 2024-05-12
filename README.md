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
### To write a python program for reading content from a CSV file.
### Developed by: NARASIMHAN S
### Register Number: 212223230133
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Narasimhan05/Read-from-CSV/assets/132819871/c72d8a34-16f3-40c4-a1a6-6d15fd5e2890)
![image](https://github.com/Narasimhan05/Read-from-CSV/assets/132819871/b09630e9-9a91-4ff6-bbf8-cc7be2c27ffc)

## RESULT:
