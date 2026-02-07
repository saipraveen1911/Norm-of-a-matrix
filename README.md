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
```Python
# Register No: 212225230239
# Developed By: Sai Praveen C
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1916" height="852" alt="Ex 7(a) Maths for AI" src="https://github.com/user-attachments/assets/7b806270-3b4e-4bb1-84e5-4108d7dc99b4" />


### 2-Norm of a Matrix

<img width="1910" height="867" alt="Ex 7(b) Maths for AI" src="https://github.com/user-attachments/assets/fb6a75c6-6e31-4189-9bf3-dbc73a777b88" />


### Infinity Norm of a Matrix

<img width="1881" height="862" alt="image" src="https://github.com/user-attachments/assets/f8727dbf-bccf-4949-8363-177d5b398f0b" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
