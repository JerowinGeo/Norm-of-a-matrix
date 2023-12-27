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
Program to find 1-norm, 2-norm and infinity norm of the matrix.
Developed by: Jerowin Geo J A
RegisterNumber: 212223100016

# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/cdc6dff5-71d4-4cb2-825a-448f526efcd4)


### 2-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/7fc4a7a1-3dca-4288-9098-41aaf2939df6)


### Infinity Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/78345365-46b8-4550-b010-77ab960c46c8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
