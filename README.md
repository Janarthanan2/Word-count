# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file object and get file name from the user

### Step 2:
Open the file given by the user

### Step 3:
Using for loop acess the file

### Step 4:
Use split funtion to separate the words

### Step 5:
The words is then counted by len function

### Step 6:
Print the number of words

## PROGRAM:
```
'''
Program to find for getting the word count from a text.
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051
'''
fname = input('Enter the name :')
num_words = 0
with open(fname,'r') as f :
    for line in f:
        words=line.split()
        num_words += len(words)
print('Numbers of words: ',num_words)

```
## OUTPUT:



## RESULT:
Thus the program is written to find the word count from a text.
