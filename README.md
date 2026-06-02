# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:

#Program to find the rank of a matrix.

#Developed by: monesh s

#RegisterNumber: 212225040256

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[1, 2, 3],
              [3, 6, 9]])

print(np.linalg.matrix_rank(A))

## Output:
<img width="1287" height="188" alt="Screenshot 2026-06-02 173716" src="https://github.com/user-attachments/assets/d1ff7659-2d6e-47e7-91f9-6536803ab3dc" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

