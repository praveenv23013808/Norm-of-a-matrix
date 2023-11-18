# Norm of a matrix
EX 07 Norm of a matrix
Date: 03.10.2023
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
Program to find 2-norm of a matrix.
Developed by:PRAVEEN V
RegisterNumber: 23013808
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
'''
Program to find 2-norm of a matrix.
Developed by:PRAVEEN V
RegisterNumber: 23013808
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
# Type your code here
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-11-18 103207](https://github.com/praveenv23013808/Norm-of-a-matrix/assets/145824728/7ce299ed-302c-4a48-8e05-efece92fd260)
### 2-Norm of a Matrix
![Screenshot 2023-11-18 103239](https://github.com/praveenv23013808/Norm-of-a-matrix/assets/145824728/55bdec58-5e1c-4835-92d1-013806dbd16f)
### Infinity Norm of a Matrix
![Screenshot 2023-11-18 103310](https://github.com/praveenv23013808/Norm-of-a-matrix/assets/145824728/f0ec7b72-b0f9-4849-8abf-1774cb6e5858)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
