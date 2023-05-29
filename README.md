# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program. 

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Tharika S
RegisterNumber: 212222230159
'''
import numpy as np 
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Tharika S
RegisterNumber: 212222230159
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
(i) To find the L and U matrix
![Screenshot (18)](https://github.com/tharikasankar/LU-Decomposition/assets/119475507/e54cc40b-5133-4a66-b4b6-53ca0623897e)
(ii) To find the LU Decomposition of a matrix
![Screenshot (19)](https://github.com/tharikasankar/LU-Decomposition/assets/119475507/55d0c73d-a347-45a7-a393-0493d7842ce3)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

