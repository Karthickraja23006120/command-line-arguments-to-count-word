# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 open the file sys.argv[1] in read mode
### Step 3: 
read the opened file and assign to a1
### Step 4:  
split the a1
### Step 5: 
print the a1
### Step 6: 
end the program
## PROGRAM:
```
Developed by: Karthick Raja K
Reference Number:23006120
import sys
f=open(sys.argv[1],'r')
a1=f.read()
a.split()
print(len(a))
```
### OUTPUT:
![output](/Screenshot%202023-08-01%20085201.png)
![output](/myfile.txt)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
