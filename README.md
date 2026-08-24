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
# Register No:212224230058
# Developed By:Dhanus karthi S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<img width="639" height="271" alt="image" src="https://github.com/user-attachments/assets/6046ea5f-0cb0-41ff-b091-fd6de2b7b44c" />


### 2-Norm of a Matrix
<img width="613" height="322" alt="image" src="https://github.com/user-attachments/assets/3fde196a-34f5-46de-b858-be54b762440d" />

### Infinity Norm of a Matrix

<img width="532" height="359" alt="image" src="https://github.com/user-attachments/assets/482426cb-79ba-4b36-8ef0-a3d7b04c7017" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
