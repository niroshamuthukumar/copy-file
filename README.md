# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open the file in which we want to copy from and access it in read mode
### Step 2: 
 read the file and store in a variable. 
### Step 3: 
now create a new file in which we want to paste the content using write access mode.
### Step 4:  
use write functions to copy the read file that has been stored in the variable.
### Step 5: 
the content in the original file will be copied in the new file
### Step 6: 
end the program
## PROGRAM:
```
Developed by: Nirosha M
Register Num: 23014438

with open("sample.txt","r") as firstfile:
    with open("sample2.txt","a")as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:
![Screenshot 2023-12-29 122031](https://github.com/niroshamuthukumar/copy-file/assets/151830921/abbd76b0-df66-4cc3-ae71-c3ce1e44d35d)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
