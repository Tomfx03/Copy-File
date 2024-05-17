# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
1. Get the file name and location from the user.
2.Give a new file name to create a copy of a file content.
3.Read the file and close the file.
4.Now write the content in the new file.
5.When done print "File copied sucessfully"
6.End of the program.
## PROGRAM:
```
Developed BY TOM FRANCIES XAVIOUR L
Reg No: 212223110060
print("Enter the name of source file:")
sFile=input()
print("Enter the name of target file:")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandle=open(tFile,"w")
for s in texts:
fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```

### OUTPUT:
![Screenshot 2024-05-17 091130](https://github.com/Tomfx03/Copy-File/assets/101335832/ddee3174-688c-4183-babe-530af553fc4e)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
