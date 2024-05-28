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
# Register No: VASANTH KUMAR V
# Developed By: 2305002027
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
### 1-Norm of a Matrix:
![image](https://github.com/vasanth0228/Norm-of-a-matrix/assets/155505264/c66aa9c1-bd85-4f54-a1dd-35e915ff0809)

### 2-Norm of a Matrix:
![Screenshot 2024-05-28 135821](https://github.com/vasanth0228/Norm-of-a-matrix/assets/155505264/d2dff7d0-5d32-4311-92ad-c519a4df2d54)

### Infinity Norm of a Matrix:
![image](https://github.com/vasanth0228/Norm-of-a-matrix/assets/155505264/709d0ce5-6bdc-4698-a3d2-274be917febd)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
