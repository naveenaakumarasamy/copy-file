# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program

## PROGRAM:

Developed by: naveenaa A.K
RegisterNumber: 22003091

with open('navee.txt','r') as f3:
    with open ('navee4.txt','a') as f4:
        for line in f3:
            f4.write(line)
            

### OUTPUT:
![append](https://user-images.githubusercontent.com/113497406/194220019-1264a050-cac1-47da-9a05-60ca7efe3170.png)

Text file:
![append1](https://user-images.githubusercontent.com/113497406/194220077-130bbf7d-dd55-4e5f-8a77-6d99a180ab09.png)


Copy file:
![append2](https://user-images.githubusercontent.com/113497406/194220107-c8703a55-713a-43d9-a82b-1c5af47ff1f4.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
