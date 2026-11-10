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
# Register No: 26018300
# Developed By: M.K. JEEVITH
# 1-Norm of a Matrix
'''
Programe to find 1-norm of matrix
Developed by : M.K. JEEVITH
RegisterNumber:26018300
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: M.K. jeevith
RegisterNumber: 20618300
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
'''
Programe to find infinity of matrix
Developed by : M.K.JEEVITH
RegisterNumber:26018300
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/4bfda26b-2617-4abe-9289-aff3f4e3390d" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/bd1ecc7d-2889-4744-b919-7167482d4298" />

### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/0b83b050-d51a-4bd4-bef9-360aa05307e4" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
