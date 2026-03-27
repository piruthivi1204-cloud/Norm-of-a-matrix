# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step 1.
	Get the input matrix using np.array()  
	
### step 2.
    Find the 2-norm of the matrix using np.linalg.norm()
### step 3.
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:Piruthiviraj G
# Developed By:212225040299
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
<br>
<br>
<br>
<img width="1204" height="879" alt="image" src="https://github.com/user-attachments/assets/e283ef85-2935-483f-aa05-6dddc32fef05" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1185" height="874" alt="image" src="https://github.com/user-attachments/assets/56956517-1173-4db9-8f24-d2ff5dd20bc4" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1197" height="876" alt="image" src="https://github.com/user-attachments/assets/2e091d4c-1c26-45cf-bca3-0d9fbf29de47" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
