# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create the file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```python
#Developed by : BHUMIREDDY LAKSHMI VARDHAN REDDYU
#Reference no : 23009662

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![COPY](https://github.com/BhumireddyLakshmivardhanreddy/copy-file/assets/148514637/0b1626dc-616c-4ab7-8d58-c5591d98f5cd)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
