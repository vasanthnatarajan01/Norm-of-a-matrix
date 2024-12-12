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
# Register No: VASANTH N
# Developed By: 24000697
# 1-Norm of a Matrix

	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,1)
	norm_of_matrix = "{:.2f}".format(ans)
	print(norm_of_matrix)


# 2-Norm of a Matrix

	import numpy as np
	mat =np.array(eval(input()))
	ans = np.linalg.norm(mat,2)
	norm_of_matrix="{:.2f}".format(ans)
	print(norm_of_matrix)
	

# Infinity Norm of a Matrix

	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,np.inf)
	norm_of_matrix = "{:.2f}".format(ans)
	print(norm_of_matrix)


## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-12 175937](https://github.com/user-attachments/assets/ed8c332f-dc43-4460-b5a7-afd73f6924e5)


### 2-Norm of a Matrix
![Screenshot 2024-12-12 180000](https://github.com/user-attachments/assets/ff335186-c7df-4030-a14f-aa3bb56311dd)


### Infinity Norm of a Matrix
![Screenshot 2024-12-12 180027](https://github.com/user-attachments/assets/4dfc966a-cf5c-41a5-bc79-71c43899936c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
