# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the nested list of matrix for each row and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: End the program

## Program:
#Program to find the inverse of a matrix.

#Developed by: E Prasanth

#RegisterNumber: 212221233002

import numpy as np

matrix = np.array([[1, 0, 3], [-1, 2, -2], [2, 3, -1]])

inverse_matrix = np.linalg.inv(matrix)

print(inverse_matrix)

## Output:
![Screenshot (16)](https://github.com/PrasanthE2001/INVERSE-OF-A-MATRIX/assets/114572171/acc9a08b-cbb3-43ee-9321-bf470f19c68b)

## Result:
Thus the inverse of given matrix is successfully solved using python program.

