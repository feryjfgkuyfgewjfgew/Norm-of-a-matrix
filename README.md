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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-25 060233](https://github.com/feryjfgkuyfgewjfgew/Norm-of-a-matrix/assets/150319377/56139c51-6160-439d-8b15-a7e0f731fcba)


### 2-Norm of a Matrix
![Screenshot 2023-12-25 060246](https://github.com/feryjfgkuyfgewjfgew/Norm-of-a-matrix/assets/150319377/3b0d8452-96e1-4bd1-8a36-001846d07f7e)

### Infinity Norm of a Matrix
![Screenshot 2023-12-25 060259](https://github.com/feryjfgkuyfgewjfgew/Norm-of-a-matrix/assets/150319377/66ffeffd-62ed-4142-a241-bd28be636217)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
