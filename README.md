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
# Register No: Gokul C
# Developed By: 212223240040
# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")


# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")


# Infinity Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-04-16 205621](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/91296174-2a08-46c8-89bb-ccf18f7c0a73)

![Screenshot 2024-04-16 205639](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/fc939b15-3d8f-40cb-8fa7-e5b9964a66dd)


### 2-Norm of a Matrix

![Screenshot 2024-04-16 205703](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/f36fdb02-d9d4-4d3a-98ef-841ecd4ab22d)

![Screenshot 2024-04-16 205723](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/b6e71a0d-ee07-4f72-97bd-4ef0b93fca95)



### Infinity Norm of a Matrix

![Screenshot 2024-04-16 205739](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/e69c6a81-bc28-4d89-8cd3-64ec9db02765)

![Screenshot 2024-04-16 205753](https://github.com/Gokul1410/Norm-of-a-matrix/assets/153058321/06caad15-fdaf-4139-8bf7-9789871722a4)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
