# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code

### Step 2: 
Create file with .py extension.
 
### Step 3:
Start the program.

### Step 4:  
Write the code.

### Step 5:
Run terminal for output of the given program

### Step 6: 
End the program

## PROGRAM:

Developed by : NATHIN R

Register Number : 22008510

```
num_words = 0
with open('Text.txt','r') as f1:
    for i in f1:
        words=i.split()
        num_words+= len(words)
print("Number of words in the file = {}".format(num_words))

```
### OUTPUT:


![image](https://user-images.githubusercontent.com/118679646/214828153-fa98a0fb-9a65-47cb-ad68-b454818ea7bf.png)


![WhatsApp Image 2023-01-26 at 17 14 29](https://user-images.githubusercontent.com/118679646/214827764-1d4b1dda-ca2b-49df-9e21-9c7da14c932b.jpg)




## RESULT:
Thus the program is written to find the word count from a text.
