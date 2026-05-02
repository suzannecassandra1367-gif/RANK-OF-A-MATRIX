# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and import the required libraries (numpy for matrix operations).
### Step 2: Define the matrix A with the given elements.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the result (rank of the matrix) and end the program.


## Program:
#Program to find the rank of a matrix.
#Developed by:Cassandra Suzanne F 
#RegisterNumber:212225240027
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A = np.array([[5, -3, -10],
              [2, 2, -3],
              [-3, -1, 5]])
rank = np.linalg.matrix_rank(A)
print(rank)

## Output:
<img width="927" height="216" alt="image" src="https://github.com/user-attachments/assets/6c113376-1aa2-4ebc-ab79-cad9252b0355" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

