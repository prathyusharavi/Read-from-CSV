# Read-from-CSV

## AIM:
To write the program for reading a CSV file

## ALGORITHM:
### Step 1:
Import pandas library using import statement.

### Step 2:
Read the contents of the given csv file using read_csv() method and pass the name of the file with '.csv' extension as the argument. make sure that the data file and the program are saved in the same location,otherwise mention the file's full path.

### Step 3:
Display the first few indices of the file using head() method and pass required number of indices as the argument. The default number of indices displayed in 5.

### Step 4:
Display the last few indices of the file using tail() method and pass required number of indices as the argument. The default number of indices displayed is 5.

### Step 5:
end the program

## PROGRAM:
```
Developed by: YENUGANTI PRATHYUSHA
Register No: 23009045

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/prathyusharavi/Read-from-CSV/assets/147474424/fa40ee17-f18e-4b90-ae60-316be110f0e2)
![image](https://github.com/prathyusharavi/Read-from-CSV/assets/147474424/57f77f49-c79f-48af-b839-c1be13bc3228)


## RESULT:
thus the program executed successfully.
