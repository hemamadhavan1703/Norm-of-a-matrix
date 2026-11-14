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
# Register No: 26018380
# Developed By: hema.M
# 1-Norm of a Matrix
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: HEMA.M
RegisterNumber:26018380 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<br><img width="1187" height="908" alt="Screenshot 2026-11-14 221549" src="https://github.com/user-attachments/assets/3a93e9ef-0701-4e21-a9a2-290b90311ce7" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1192" height="918" alt="Screenshot 2026-11-14 221602" src="https://github.com/user-attachments/assets/642d7186-8f65-445b-9807-9dfb88af3850" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1206" height="911" alt="Screenshot 2026-11-14 221621" src="https://github.com/user-attachments/assets/9268e6e2-ab64-4432-81f3-72fa0f4011ec" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
