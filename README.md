# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys

### Step 2: 
Open file using open().
 
### Step 3: 
Use the loop

### Step 4: 
Use len to count number of words 

### Step 5: 
Give print


## PROGRAM:
```
#program is developed: Anbuvinotha
# REF.NO: 23013363

import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("word count in file = ",count)

```


### OUTPUT:

![output](<argument ss.png>)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
