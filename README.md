# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import sys module

Step 2:
Open the file with sys.argv[1]

Step 3:
Use the for loop to select the content in file

Step 4:
Use split function to to separate the file content into words or strings

Step 5:
Count the length of the words using len

Step 6:
Print the number of words

## PROGRAM:
```
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```
### OUTPUT:

![image](https://github.com/PERARASU10/command-line-arguments-to-count-word/assets/118348589/30ac6029-d936-4bda-80c6-472f5b1478e4)

![image](https://github.com/PERARASU10/command-line-arguments-to-count-word/assets/118348589/9235251f-adf5-4981-a4a5-44f4daddf135)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
