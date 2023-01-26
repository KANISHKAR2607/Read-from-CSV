# Read-from-CSV

## AIM:

To write a python program for reading the csv file content.

## EQUIPMENTS REQUIRED:

PC Anaconda - Python 3.7

## ALGORITHM:

### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
'''
Developed By : KANISHKAR M

Referance No. : 22007816
'''
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:

![kaNI 6](https://user-images.githubusercontent.com/118886772/214779082-491d81b1-b448-4d0f-a568-602e8a1df126.png)


## RESULT:

Thus a python program is written to read the contents of a CSV file.
