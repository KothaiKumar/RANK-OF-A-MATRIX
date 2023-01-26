# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the list and arrange in np.array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
'''python
#Program to find the rank of a matrix.
#Developed by: Kothai K
#RegisterNumber:22006043

import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)

'''
## Output:
![rank_of_matrix](https://user-images.githubusercontent.com/121215739/214833203-e538c002-df1a-44e6-a027-745b82e6f6f3.png)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

