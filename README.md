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
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
 ``` 
### OUTPUT:
![244279709-07302a96-9557-4806-8236-4381000c3715](https://github.com/Yamunaasri/command-line-arguments-to-count-word/assets/115707860/60313b57-aa71-499d-a2dd-a41fb91f9f22)


![244279728-24d5bb6b-e206-4cd3-ba56-97b7837aa52e](https://github.com/Yamunaasri/command-line-arguments-to-count-word/assets/115707860/c018a526-0dd0-4d0c-94d6-b2806121fa71)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
