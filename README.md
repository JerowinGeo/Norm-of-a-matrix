# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
	1.Hardware – PCs
 	2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	1. Get the input matrix using np.array()   
 	2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
 
## Program:

```
Program to find 1-norm, 2-norm and infinity norm of a matrix.
Developed by: Jerowin Geo J A
RegisterNumber: 212223100016

1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/JerowinGeo/Norm-of-a-matrix/assets/147139744/233a4d13-e4f7-4fa6-9498-0991fce245ef)


### 2-Norm of a Matrix
![image](https://github.com/JerowinGeo/Norm-of-a-matrix/assets/147139744/3a154136-8898-4b64-847d-36ab35b60e98)


### Infinity Norm of a Matrix
![image](https://github.com/JerowinGeo/Norm-of-a-matrix/assets/147139744/59234ce5-1e6f-4d3c-8e36-7d330e053865)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
