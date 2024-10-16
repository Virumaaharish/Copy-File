# DATE :
# EXP NO : 11
# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file.
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function.

## PROGRAM:
```
#Developed by: VIRUMAA HARISH M
#Register Number: 212223230246
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/23002248/Copy-File/assets/151701774/43c36488-435a-4bf7-9f4b-cd02e75a1441)
![image](https://github.com/23002248/Copy-File/assets/151701774/6c4506b7-4280-4954-9a4a-31067dabebcd)
![image](https://github.com/23002248/Copy-File/assets/151701774/be14b461-f96c-4c58-8f76-66a446a34180)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
