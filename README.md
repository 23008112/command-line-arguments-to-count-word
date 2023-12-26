# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest

### Step 2: 
On the same location as the text file, create a python program file.
 
### Step 3: 
n python Program, import sys and open a text file with argument "sys.argv[1]"

### Step 4:  
using read() and split(), split the lines in the file into a sequence of words

### Step 5: 
using len() count the number of words in the text file

### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output

## PROGRAM:
```
#program for getting the word count from the contents of a file using command line argument
#Developed by: R.SANJANA
#Register Number:230008112

import sys
with open(sys.argv[0],'r') as f:
    num_words=0
    for i in f:
        word=i.split()
        num_words+=len(word)
print("Number of words={}".format(num_words))
```

### OUTPUT:
![Screenshot 2023-12-26 070416](https://github.com/23008112/command-line-arguments-to-count-word/assets/138972470/9bfcf148-46c5-40a1-8368-9eb688df4cfe)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
