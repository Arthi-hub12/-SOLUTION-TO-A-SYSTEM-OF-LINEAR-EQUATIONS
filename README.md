# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Register: 212225220012
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
#program to find a solution to a system of linear equations
#developedby : ARTHI S A
#registernumber : 212225220012
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix_a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
const=np.array([-9,4,-1])
result=np.linalg.solve(matrix_a,const)
print(result)
~~~
## Output:
<img width="1077" height="545" alt="Screenshot 2026-07-27 205244" src="https://github.com/user-attachments/assets/504e6f75-689d-4cfd-aabb-67d96ce93bd4" />
<img width="1067" height="232" alt="Screenshot 2026-07-27 205301" src="https://github.com/user-attachments/assets/71ba6523-387c-4449-8a31-ac264c0e9fec" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

