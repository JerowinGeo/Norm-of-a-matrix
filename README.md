# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
3.	
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
 
## Program:
```
Program to find 1-norm, 2-norm and infinity norm of a matrix.
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
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/65c2734c-4620-4dbe-867b-9f1558100309)


### 2-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/d19996c8-c63d-4071-a76b-a969ffa6f595)


### Infinity Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/147139744/8ab4e476-e964-4acd-a8b0-3de3744c4628)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
