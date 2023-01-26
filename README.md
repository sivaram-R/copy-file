# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file with .txt extension

### Step 2:
Enter some words in file.txt file.

### Step 3:
Create python notebook.

### Step 4:
Enter the code with file name as excatly given in .txt extension.

### Step 5:
Run the code ,it will copy from file to file2

### Step 6:
open the file2.txt it will copy the input and display.

## PROGRAM:
student name:sivaram R
reference no:22008680
```
with open('f1.txt','r')as firstfile:
    with open('f2.txt','a')as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/121165794/214764716-520e9e95-c420-41c7-9ff5-e8a320c9223b.png)
![Screenshot from 2023-01-26 10-30-04](https://user-images.githubusercontent.com/121165794/214764834-7725efcd-d69f-4ddf-b493-8647dcf46957.png)
![Screenshot from 2023-01-26 10-31-29](https://user-images.githubusercontent.com/121165794/214764856-20147ce5-2e55-4842-bcba-4af10b86d6f0.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
