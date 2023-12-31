# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
## Step 1:
Open the file in read mode and handle it in test mood.

## Step 2:
Read the text using read() function.

## Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

## Step 4:
The length of the split list should equal the numbers of words in the test file.

## Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

## Step 6:
End the program.




## PROGRAM:

```
Developed by : Goutham.K
Register No: 212223110019
def wordcount(filename):
    count=0
    with open("newfile.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
![image](https://github.com/Goutham2306/copy-file/assets/138971154/17b518b8-ba25-48d8-b3e3-dedb48c0f173)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
