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
# Register No:24900038
# Developed By:Tharshini

# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
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
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:

### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/d5d15a52-574e-4ac6-a1a8-5cd6b0bda17c)


### 2-Norm of a Matrix
![Screenshot 2024-11-30 234711](https://github.com/user-attachments/assets/8eaf4fca-09c2-494d-9a8b-3f7cbda89147)



### Infinity Norm of a Matrix
![Screenshot 2024-11-30 234740](https://github.com/user-attachments/assets/ab30230a-ce13-48ed-b666-cd53413eef58)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
