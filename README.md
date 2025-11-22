# SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
---
### _Program to find the solution for the given linear equations._
### _Developed by: ISRAVEL Y_
### _RegisterNumber: 25018187_
---
```py
import numpy as np
coef_matrix=np.array([[1,3],
                    [2,5]])
                    
ordinate=np.array([5,-3])

print(np.linalg.solve(coef_matrix, ordinate))

```
## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-22 133549" src="https://github.com/user-attachments/assets/7ce01c8a-a9e0-4776-a2ca-d964fe8150c6" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

