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
# Register No:212225040067
# Developed By:DHARANI A
# 1-Norm of a Matrix
import numpy as np 
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```
# 2-Norm of a Matrix
```
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```
# Infinity Norm of a Matrix
```
import numpy as np 
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```
## Output:
### 1-Norm of a Matrix
<img width="510" height="590" alt="image" src="https://github.com/user-attachments/assets/713b541a-df7e-4e80-8232-ab4a27632503" />

### 2-Norm of a Matrix
<img width="434" height="571" alt="image" src="https://github.com/user-attachments/assets/e3ac4912-7550-4006-a737-e5bf13bc6a30" />

### Infinity Norm of a Matrix
<img width="457" height="549" alt="image" src="https://github.com/user-attachments/assets/53a82368-7570-4db1-a14f-b0e01144449d" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
