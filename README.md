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
#Developed by : Logesh.N.A
#Reference no : 23012242

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

### OUTPUT:
<img width="351" alt="292658793-8d133ce1-ebfb-48bc-aab9-5db9be7043a7" src="https://github.com/Logesh051/copy-file/assets/144979188/15633026-2d2b-4487-bf92-e175cb526405">

<img width="491" alt="292658805-5e238b8a-0dc9-46bc-94a7-af0d9de7877b" src="https://github.com/Logesh051/copy-file/assets/144979188/1bfdf7a2-7cc9-429a-b85c-110f2d1ae88e">


## RESULT:
Thus the program is written to copy the contents from one file to another file.
