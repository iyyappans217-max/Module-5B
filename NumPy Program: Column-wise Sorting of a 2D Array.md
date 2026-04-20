# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

rows = int(input())
cols = int(input())

arr = []
for _ in range(rows):
    arr.append(list(map(int, input().split())))

arr = np.array(arr)

sorted_arr = np.sort(arr, axis=0)

print(arr)
print(sorted_arr)
```

## Output
<img width="1922" height="988" alt="image" src="https://github.com/user-attachments/assets/6707af47-ddf6-4dfe-81b0-20c8213fa2dc" />

## Result
Hence successfully done using VSCODE.
