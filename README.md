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
~~~Python
# Register No:SANTHOSH R
# Developed By:212224230249
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
print("{:.2f}".format(ans))
# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
print("{:.2f}".format(ans))
# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, np.inf)
print("{:.2f}".format(ans))
~~~
## Output:
### 1-Norm of a Matrix
<img width="1290" height="946" alt="Screenshot 2025-10-15 190444" src="https://github.com/user-attachments/assets/bcf4e58b-b201-405d-b4f9-b3889e461cf1" />
### 2-Norm of a Matrix
<img width="1282" height="950" alt="Screenshot 2025-10-15 190525" src="https://github.com/user-attachments/assets/4e76b608-3bc8-4330-88b7-3eadd508b039" />
### Infinity Norm of a Matrix
<img width="1287" height="916" alt="Screenshot 2025-10-15 190612" src="https://github.com/user-attachments/assets/57748f86-1af7-49f6-ba49-a6ae3f47eb13" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
