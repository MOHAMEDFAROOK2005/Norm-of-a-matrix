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
# 1-Norm of a Matrix
'''
program to find 1-norm of a matrix
developed by:MOAHMED FAROOK S
registernumber:23014058
'''
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}".format(sol)
print(norm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: MOHAMED FAROK S
RegisterNumber:23014058 
'''
import numpy as np
a=([[1,2],[3,4]])
b=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)




# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix
Developed by: MOHAMED FAROK S
RegisterNumber:23014058 
'''
import numpy as np
arr=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/MOHAMEDFAROOK2005/Norm-of-a-matrix/assets/150319482/87784152-397c-4ffc-b43b-8856d39f8542)


### 2-Norm of a Matrix
![image](https://github.com/MOHAMEDFAROOK2005/Norm-of-a-matrix/assets/150319482/5cee3387-9b91-405e-94d0-101c51260b1a)


### Infinity Norm of a Matrix
![image](https://github.com/MOHAMEDFAROOK2005/Norm-of-a-matrix/assets/150319482/2d805c7d-7a74-42a3-b453-73920e0c9df5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
