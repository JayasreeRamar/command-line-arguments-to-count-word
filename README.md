# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the files as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
#Program to find the Word Count using command line arguments
#Developed by: Jayasree R
#register Number: 23009250
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
  for line in f:
    words=line.split()
    num_words+=len (words)
print('Number of words: ',num_words)

```
### OUTPUT:
![OUTPUT](<Screenshot 2024-01-02 220420.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
