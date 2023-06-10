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
![Screenshot 2023-06-10 090821](https://github.com/Janarthanan2/Word-count/assets/119393515/a883f240-6a16-4756-8cef-be1392760744)

![Screenshot 2023-06-10 091023](https://github.com/Janarthanan2/Word-count/assets/119393515/6176295d-ccb5-4253-a663-322d8a4a3dcf)

![Screenshot 2023-06-10 090925](https://github.com/Janarthanan2/Word-count/assets/119393515/f7f5ea6c-a317-4dd5-9916-53bb68e71ac3)


## RESULT:
Thus the program is written to find the word count from a text.
