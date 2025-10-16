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
# Register No: 212224240135
# Developed By: V RISHON ANAND
# 1-Norm of a Matrix
## the 1-norm of a matrix (often called the maximum column sum norm) is 
# calculated as the  ## ,aximum sum of the absolute values of the elements in each column.
 
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1247" height="828" alt="image" src="https://github.com/user-attachments/assets/c635ef1b-5bb4-420d-a3de-6e7ce969b8c4" />
<img width="1244" height="367" alt="image" src="https://github.com/user-attachments/assets/bd7ee58d-9906-4c18-b2fe-715e93947989" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1238" height="908" alt="image" src="https://github.com/user-attachments/assets/2760c2d2-eb02-4a08-9020-ee21217f3d44" />
<img width="1243" height="384" alt="image" src="https://github.com/user-attachments/assets/47dfae03-5cbe-4d2d-9761-932997cc0e73" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1240" height="793" alt="image" src="https://github.com/user-attachments/assets/67aba5e6-226a-47b1-ac6c-bbaf0da5a361" />
<img width="1235" height="344" alt="image" src="https://github.com/user-attachments/assets/73b0ffe2-469b-49dc-be66-3decf9ca0f83" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
