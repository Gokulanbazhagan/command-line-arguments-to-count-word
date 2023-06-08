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
Program for getting the word count from the contents of a file using command line arguments
Developed by: GOKULARAANAN.K
RegisterNumber: 212222230040
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![Screenshot (110)](https://github.com/Gokulanbazhagan/command-line-arguments-to-count-word/assets/119518996/4cbbe1d2-15bc-42b2-b4eb-8122f106cb82)
![Screenshot (112)](https://github.com/Gokulanbazhagan/command-line-arguments-to-count-word/assets/119518996/854ff197-03f4-433f-b960-2ee1b6847d75)
![Screenshot (114)](https://github.com/Gokulanbazhagan/command-line-arguments-to-count-word/assets/119518996/b474d1ca-3d2a-4959-a837-b1766fd50732)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
