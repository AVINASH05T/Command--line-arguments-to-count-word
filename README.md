# Command--line-arguments-to-count-word
### NAME: AVINASH T
### REG NO: 212223230026
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.
### Step 2: 
Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
### Step 7:
Close the file pointer and end the program
## PROGRAM:
```c
#Command line arguments - word count
#Developed by: AVINASH T
#Register number:212223230026
import sys
count=0
with open(sys.srgv[1],'r')as f1:
    for line in f1:
        word=line.split()
        count += len(word)
    print("word count in file = ",count)
```
### OUTPUT:
![image](https://github.com/AVINASH05T/Command--line-arguments-to-count-word/assets/151514286/b2e001d9-7604-4fd0-b459-dde3596ac72f)
![image](https://github.com/AVINASH05T/Command--line-arguments-to-count-word/assets/151514286/bfabee54-8a50-4d43-ac90-a28ff293f741)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
