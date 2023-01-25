# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a txt file to count the number of word in that file.

### Step 2: 
 Open the txt file in read mode using open().

### Step 3: 
Using split() function to split the words in the txt file and count it.

### Step 4:  
Using split() function to split the words in the txt file and count it.

### Step 5: 
Run the python program in terminal to get the output.

### Step 6:
Run the python program in terminal to get the output.








## PROGRAM:
```
Developed by:Nirosha.S
Register number:22009078

num_words =0
with open('python.py','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={0}".format(num_words))
```

### OUTPUT:
![](n1.jpg)

![](n2.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
