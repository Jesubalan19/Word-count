# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
Give the input string. 
### Step 3: 
Print the original string.
### Step 4:  
using len(test_string.split()) get the result.
### Step 5: 
Print the word count.
### Step 6: 
End the program.
## PROGRAM:
```
#Program for word count
#Developed by : Jesubalan A
#Reference number : 23013427

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```
### OUTPUT:
![Ex 5a](https://github.com/Jesubalan19/Word-count/assets/144979294/511f6945-232a-438c-8b9f-becdf788bc71)



## RESULT:
Thus the program is written to find the word count from a text.
