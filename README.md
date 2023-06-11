# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC,Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.
 

## PROGRAM:
```
#Developed By: S.Jaiganesh
#Register No: 212222240037
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```            
## OUTPUT:
### File 1:
![image](https://github.com/Jaiganesh235/copy-file/assets/118657189/222d3dc2-3c57-43ba-b1f7-b57b12c93437)

### File 2:
![image](https://github.com/Jaiganesh235/copy-file/assets/118657189/62f85a42-0f63-4069-a31e-f03d495d48a0)

### File 1 copied to File 2:
![image](https://github.com/Jaiganesh235/copy-file/assets/118657189/df7e2a87-c56b-4fbe-bc47-d231215b3961)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
