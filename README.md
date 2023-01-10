# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy
2. From scipy.linalg import lu ,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval 
4. Using P,L,U=lu(A) we can find L and U matrix . 
   Using res=lu_factor(A) ,solution=lu_solve(res,B) we can find LU Decomposition of a matrix.
5. Print the respective outputs and end the program

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Amrutha Rajsheker 
RegisterNumber: 22004501

import numpy
from scipy.linalg import lu
arr=eval(input())
A=numpy.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Amrutha Rajsheker 
RegisterNumber: 22004501

#To print X matrix (solution to the equations)
import numpy
from scipy.linalg import lu_factor,lu_solve
A=numpy.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
(i) To find the L and U matrix
![5 1](https://user-images.githubusercontent.com/119475943/211498343-af2f487e-8fff-43d4-8f8f-317c26493e9b.png)

(ii) To find the LU Decomposition of a matrix
![5 2](https://user-images.githubusercontent.com/119475943/211498424-98167372-c5ba-4d9b-a4e9-5669ba85337b.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

