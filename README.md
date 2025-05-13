# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```Python
#Developed by: DINESH R
#RegisterNumber: 212224240037
# 1-Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,1)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)   

# 2-Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,2)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)

# Infinity Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,np.inf)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e490fdd8-67e7-45dd-9fce-798322f44078)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/5252c470-38c0-4e45-8f27-09df0c45dd26)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/6bd7ad45-3944-4e04-af80-2086b0b140ab)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
