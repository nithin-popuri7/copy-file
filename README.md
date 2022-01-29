# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start.

### Step 2:
Open the first file in read mode by an appropriate method.
 
### Step 3: 
Open the second file in write mode by an appropriate method.

### Step 4: 
Loop until variable 'i' in the first file.so variable i propogates all over the content.

### Step 5: 
Write the value of 'i' in the file by following method.secondfileName.write(i)

### Step 6: 
stop

## PROGRAM:
```
Developed By:Popuri Siva Naga Nithin
Reference No:21003942
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
      
    # read content from first file
    for line in firstfile:
               
             # append content to second file
             secondfile.write(line)
```

### OUTPUT:
![Github Logo](copy.png)
![Github Logo](copy1.png)
![Github Logo](copy2.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
