# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2: 
Read the text using read() function.

 
### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space
character

### Step 4:
The length of the split list should equal the numbers of words in the test file.


### Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after
splitting.

### Step 6: 
End the program.

## PROGRAM:
```
#Program to find the number of words in a txt file.
#Developed by: MS Dharanish
#Reg no:212223240027
num=0
with open("file.txt","r") as f1:
for i in f1:
word=i.split()
num+=len(word)
print("The number of words in the file is ",num)
```

### OUTPUT:
![output 1](https://github.com/MSDharanish-23011819/Word-count/assets/147139454/660a0838-53fc-4ac9-87a3-2de2a5c44714)

![output 2](https://github.com/MSDharanish-23011819/Word-count/assets/147139454/778d65e9-c7f5-4486-9b90-66143c21ed29)


## RESULT:
Thus the program is written to find the word count from a text.
