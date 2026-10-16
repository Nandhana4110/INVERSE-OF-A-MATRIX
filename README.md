# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the solutions.
### Step 4: End the program
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = np.array([[2,1,1],[1,1,1],[1,-1,2]])
r = np.linalg.inv(a)
print(r)
## Output:
<img width="1327" height="866" alt="image" src="https://github.com/user-attachments/assets/4162573a-b069-4079-92fb-82b5e4221a5f" />
## Result:
Thus the inverse of given matrix is successfully solved using python program
