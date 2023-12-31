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
Developed By:Goutham.K
Register No: 212223110019
try:
    with open("myfile.txt", 'r') as source:
        content = source.read()

    with open("output.txt", 'w') as destination:
        destination.write(content)

    print("File copied successfully!")
    
    with open("output.txt",'r') as fp:
        data = fp.read()
        
    print(f"Copied content:\n{data}")

except FileNotFoundError:
    print("One or both files not found.")
except Exception as e:
    print(f"An error occurred: {str(e)}")
```

### OUTPUT:
![image](https://github.com/Goutham2306/copy-file/assets/138971154/1cbaa31a-bd65-4e82-be6a-d8e3b567c56e)



![image](https://github.com/Goutham2306/copy-file/assets/138971154/e9a3d685-23c1-4480-8fbf-c990b8be310f)



![image](https://github.com/Goutham2306/copy-file/assets/138971154/8a3c8f08-a65a-49a3-9421-d44eefb198c8)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
