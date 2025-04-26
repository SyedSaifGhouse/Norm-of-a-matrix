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

### Register No : 212224230286
### Developed By : SYED SAIF SYED GHOUSE
### 1-Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))
~~~





### 2-Norm of a Matrix

```
import numpy as np
a= np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))
```



### Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/1229056e-a21c-4d3b-b5e0-dd19aae560f0)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/16d07449-93c6-4faa-8a82-99ccc1ed3808)



### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/1ec15b44-2b4e-431f-b663-5f836bf82b73)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
