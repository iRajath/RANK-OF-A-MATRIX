# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to utilize its built-in functions for calculations
### Step 2: Prepare the lists from each linear equation and assign them to `np.array()`
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: S Rajath
#RegisterNumber: 24900186

import numpy as np

a = np.array([[1, 2, 3], [3, 6, 9]])
solution = np.linalg.matrix_rank(a)
print(solution)
```

## Output:

![Screenshot 2024-12-04 135325](https://github.com/user-attachments/assets/7839c049-278a-4902-af3b-5ca6ed546d1e)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

