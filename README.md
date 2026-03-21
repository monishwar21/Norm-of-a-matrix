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
# Register No:212225230188
# Developed By: MONISHWAR K
# 1-Norm of a Matrix


1. One norm
import numpy as np
A=np.array(eval(input()))
onenorm=np.linalg.norm(A,1)
print(onenorm)


# 2-Norm of a Matrix
2.  Two norm
import numpy as np
A=np.array(eval(input()))
twonorm=np.linalg.norm(A,2)
print(f"{twonorm:.2f}")


# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
twonorm=np.linalg.norm(A,np.inf)
print(f"{twonorm:.2f}")




```
## Output:
### 1-Norm of a Matrix

<img width="648" height="292" alt="Screenshot 2026-03-21 205836" src="https://github.com/user-attachments/assets/fd6248b9-e8da-47e0-b618-429ab41428ce" />

<br>
<br>
<br>

### 2-Norm of a Matrix

<img width="825" height="253" alt="Screenshot 2026-03-21 210206" src="https://github.com/user-attachments/assets/971be478-34ae-4eb9-90ba-7acd9f960aff" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="762" height="274" alt="Screenshot 2026-03-21 210307" src="https://github.com/user-attachments/assets/b4421df8-e9ce-4994-9073-aeee0c9f6846" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
