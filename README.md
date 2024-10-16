
## DATE:
## Ex No 11 -  Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output
## PROGRAM:
```


#Program for copying the contents from one file to another file.
#Developed by VIRUMAA HARISH M
#Reg num : 212223230246


with open("file.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)








```
## OUTPUT:
### file.txt
![image](https://github.com/user-attachments/assets/2a333748-78ac-42bd-8858-ebe2603246bc)
### Python File Execution
![image](https://github.com/user-attachments/assets/4983063c-5887-4576-a4ee-39f975ca5494)
### copy.txt
![image](https://github.com/user-attachments/assets/9dde4077-7d4f-4393-8d7f-a108ed4ac914)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
