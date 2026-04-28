# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# Name:Nivetha N
# Reg.no:212225040290

## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
const=np.array([-9,4,-1])
result=np.linalg.solve(matrix,const)
print(result)
~~~

## Output:
<img width="1298" height="768" alt="image" src="https://github.com/user-attachments/assets/f2839a37-9771-4ada-a4e1-a4887cd9de85" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program.

