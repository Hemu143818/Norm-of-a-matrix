# Norm of a matrix
## Aim
## date: 22-04-2025
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Input a matrix from the user in Python list format (e.g., [[1, 2], [3, 4]])
2. Convert the input into a NumPy array
3. Calculate the 2-norm (spectral norm) of the matrix using NumPy's linalg.norm function with ord=2
4. Format the result to 2 decimal places
5. Print the formatted result
## Program:
```Python
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:K HEMANTH YADAV
RegisterNumber: 212224100033
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
a="{:.2f}".format(ans)
print(a)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:k hemanth yadav 
RegisterNumber: 212224100033
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
a="{:.2f}".format(ans)
print(a)



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:k hemanth yadav 
RegisterNumber: 212224100033
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/ca658d6b-1afa-47cd-af13-2e5d86d190ee)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/ab239368-e6e2-447e-b720-7bb996716b90)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/b6ec09a9-dc02-45f5-ba71-51e63263afc7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
