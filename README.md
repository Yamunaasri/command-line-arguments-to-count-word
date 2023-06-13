# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
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
Program to count the number of words in a file
Developed by: T S Yamunaasri
Register Number: 21222240117
'''
fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
 for line in f:
  word=line.split()
  words+=len(word)
  print("Number of words:",words)
  
 ``` 
### OUTPUT:
![Screenshot 2023-06-13 161635](https://github.com/Yamunaasri/command-line-arguments-to-count-word/assets/115707860/6cd747b7-e127-4c14-8a73-554899002485)


![Screenshot 2023-06-13 161641](https://github.com/Yamunaasri/command-line-arguments-to-count-word/assets/115707860/fd53e542-1786-48fa-822b-6f27b51c6964)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
