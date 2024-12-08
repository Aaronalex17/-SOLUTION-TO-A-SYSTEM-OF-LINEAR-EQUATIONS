# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
```
import numpy as np

# Coefficients of the system of equations
A = np.array([[1, -3],  # Coefficients of x and y in the first equation
              [3, 1]])  # Coefficients of x and y in the second equation

# Right-hand side values of the system
B = np.array([0, 10])  # Constants of the equations

# Solving the system of equations
solution = np.linalg.solve(A, B)

# Display the solution
print(solution)

```

## Output:
![Screenshot (42)](https://github.com/user-attachments/assets/6aa5172a-d4bc-48fc-8eb2-d09f60c5873d)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

