# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open a file in which we want to copy from and access it in read mode
### Step 2: 
 read the file and store in variable
### Step 3: 
now create a new file in which we want to paste the content using write access mode
### Step 4:  
use write function to copy the read file that has been stored in the variable
### Step 5: 
the content in the original file will be copied in the neww file
### Step 6: 
end the program
## PROGRAM:
```
with open('original.txt','r') as fp:
 msg1=fb.read()
with open('copy.txt','a')as fp1:
 fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2024-01-02 215815](https://github.com/Harishragaventhira/copy-file/assets/145548269/77769b10-f588-4fd2-ab1e-4311b8b2ec5f)
![Screenshot 2024-01-02 215830](https://github.com/Harishragaventhira/copy-file/assets/145548269/9b521508-fa76-4ae2-92ea-a2901b043c88)
![Screenshot 2024-01-02 215844](https://github.com/Harishragaventhira/copy-file/assets/145548269/c7e8bf05-6d07-4b52-969b-4c58b3eec8a3)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
