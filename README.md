# DATE:
# EXP.NO: 07
# Norm of a matrix
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
Python
# Register No:24900303
# Developed By:RUDESH KANNA R
```
# 1-Norm of a Matrix
import numpy as np</br>
mat =np.array(eval(input()))</br>
ans=np.linalg.norm(mat,1)</br>
norm_of_matrix = "{:.2f}".format(ans)</br>
print(norm_of_matrix)</br>
```
```
# 2-Norm of a Matrix

import numpy as np</br>
mat=np.array(eval(input()))</br>
ans=np.linalg.norm(mat,2)</br>
norm_of_matrix='{:.2f}'.format(ans)</br>
print(norm_of_matrix)</br>

```
```
# Infinity Norm of a Matrix


import numpy as np</br>
mat=np.array(eval(input()))</br>
ans=np.linalg.norm(mat,np.inf)</br>
norm_of_matrix="{:.2f}".format(ans)</br>
print(norm_of_matrix)</br>
```
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/3121573e-9686-4d64-8e68-9f142be4b11d)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/0a4c01ae-1f82-4b81-84b5-bc89026d1386)

### 3-Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/d6a856ef-c792-4362-a85c-9abd45fb9702)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
