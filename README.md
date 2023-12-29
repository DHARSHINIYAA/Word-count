# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
~~~
#Program for getting the word count from the contents of a file using command line arg
#Developed by: GOWTHAM N
#Register Number : 23013437
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
~~~

### OUTPUT:
![OUTPUT](https://github.com/DHARSHINIYAA/Word-count/assets/149560172/1b4f633a-df97-4284-90df-aac1865c75d8)
## RESULT:
Thus the program is written to find the word count from a text.
