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
# Register No: 23007931
# Developed By: paida ram sai
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-15 221917](https://github.com/ramsai22/Norm-of-a-matrix/assets/150319855/3a134ffe-fee7-49fd-a2ec-c76a4ecf2a25)


### 2-Norm of a Matrix
![Screenshot 2023-12-15 222420](https://github.com/ramsai22/Norm-of-a-matrix/assets/150319855/1e6ce025-e9b1-4d7e-a03b-997c931f1748)

### Infinity Norm of a Matrix
![Screenshot 2023-12-15 222447](https://github.com/ramsai22/Norm-of-a-matrix/assets/150319855/13c01a27-c72e-4ab5-9391-2d332703dce2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
