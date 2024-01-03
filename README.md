# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Get the name of the file as an input from the user and initialize it to fname
### Step 2: 
 Initialize the count variable as 0.
### Step 3: 
open the file using the variable fname.
### Step 4:  
Use for loop to iterate through the words
### Step 5: 
Using len() function as the number of words to the count variable.
### Step 6: 
Print the output

## PROGRAM:
```
fname=input("Enter the File Name: ")
num=0
with open(fname,'r') as file:
    for line in file:
        word=line.split()
        num+=len(word)
print("Number of Words: ",num)
```
### OUTPUT:

![Screenshot 2024-01-02 232300](https://github.com/Srikaavyaathamizh/command-line-arguments-to-count-word/assets/144870938/6ff2b131-a039-4825-9c95-d5fbf0ad8c04)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
