# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open vscode.

### Step 2:
Type the program.

### Step 3:
save the python file.

### Step 4:
create a text file .

### Step 5:
Run the program in the vscode, in the terminal type the following commands.

### Step 6:
End the program.

## PROGRAM:
```
program to find word-count
#Developed by: sabari s
#Reference No: 22008698
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:

![WhatsApp Image 2023-01-26 at 16 39 07](https://user-images.githubusercontent.com/118660461/214825054-63bc1d71-1889-40c7-b454-53cf93eb101d.jpg)


![WhatsApp Image 2023-01-26 at 16 39 08](https://user-images.githubusercontent.com/118660461/214825069-781e91b7-0304-411c-bd18-ff3b55c8d24c.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
