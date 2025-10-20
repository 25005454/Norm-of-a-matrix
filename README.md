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
# Register No:25005454
# Developed By:vamsi
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
### 1-Norm of a Matrix


<img width="867" height="319" alt="image" src="https://github.com/user-attachments/assets/c45eb308-ce24-4f1b-a7dc-c094d3ae9efd" />



### 2-Norm of a Matrix

<img width="896" height="382" alt="image" src="https://github.com/user-attachments/assets/cef3ec8e-e4ac-4cc4-8d6c-b1950d632409" />



### Infinity Norm of a Matrix

<img width="1087" height="320" alt="image" src="https://github.com/user-attachments/assets/ff28de09-4899-42ee-9342-fe26cd3ddb6e" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
