# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

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
