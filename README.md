# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function:

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: SUBIKSHAN.P
RegisterNumber: 23003939

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/subikshan2006/copy-file/assets/139841805/1bfce8da-45dc-48a3-a89e-5775c0d837fe)
![image](https://github.com/subikshan2006/copy-file/assets/139841805/f3d15ed1-0ac3-4cbf-b06d-ab5c6af4d12d)
![image](https://github.com/subikshan2006/copy-file/assets/139841805/79c23e74-75a9-4b39-884f-927cad019caf)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
