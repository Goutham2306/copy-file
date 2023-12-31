# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Open the Source File for Reading:

Use the open function with the 'r' mode to open the source file ('data_file.txt') for reading.
Assign the file object to the variable source.
### Step 2:
Read Content from Source File:

Use the read method on the source file object to read the content of the source file.
Assign the content to the variable content.
### Step 3:
Open the Destination File for Writing:

Use the open function with the 'w' mode to open the destination file ('output.txt') for writing.
Assign the file object to the variable destination.
### Step 4:
Write Content to Destination File:

Use the write method on the destination file object to write the content to the destination file.
### Step 5:
Print Success Message:

If the file copy operation is successful without errors, print "File copied successfully!".
### Step 6:
Read and Print Copied Content:

Open the destination file ('output.txt') for reading.
Read the content from the destination file and assign it to the variable data.
Print the copied content using print(f"Copied content:\n{data}").



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
