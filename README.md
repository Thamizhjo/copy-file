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
End the program.
## PROGRAM:
```
Developed by: Thamizh kumaran P S
Ref.no:23004070
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### FILE:
![image](https://user-images.githubusercontent.com/119389139/215118151-7ccd79f8-e06c-43bd-877e-983d2d3ae3b4.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/119389139/215118371-26568a26-2f45-46fc-85d9-58466f26a728.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
