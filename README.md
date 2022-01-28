# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Create one text file with some contents and one empty file.
### Step 2:
Open the file which contains the content in reading mode and naming as firstfile
### Step 3: 
Then open the second empty file in append mode and name it as secondfile
### Step 4: 
Using for loop, read the contents from first file.
### Step 5:  
To append contents to second file ,use secondfile.write() 
### Step 6: 
Now run the terminal and check whether the contents copied or not.

## PROGRAM:
~~~
##Developed by : NaveenKumar.S
##Reg no : 21500481

with open('file1.txt','r') as firstfile, open('file2.txt','a') as secondfile:
# read content from first file
    for line in firstfile:
# append content to second file
        secondfile.write(line)

~~~        

### OUTPUT:
![contents_of_file_1](./file.png)
![output](./file1.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.