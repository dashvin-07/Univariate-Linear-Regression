# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program
```Python
# Register No:212224100008
# Developed By: Dashvin S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output
### 1-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/6fd37633-9b4f-4eac-8ac4-15eadf999d19)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/a08194f5-a8e2-46cd-8d5b-aa9a18c3807c)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/a8b1cf21-73e1-4348-9c5c-f12a87bbe377)

<br>
<br>


## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
