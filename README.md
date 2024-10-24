# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
![image](https://github.com/user-attachments/assets/e9f160ce-7cb6-414e-92b5-536a320bb8b8)


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/user-attachments/assets/86cb7f7f-19ec-4852-bba2-ccec0b66c518)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/user-attachments/assets/a6a4b1a9-5165-4c5a-942c-99ba9a1bdc44)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/user-attachments/assets/49cbdc2f-5dc3-4aea-971d-f08c57ce17ae)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/user-attachments/assets/c10fce9e-310c-4b23-a171-3f08a148394f)




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully
```





## OUTPUT
![image](https://github.com/user-attachments/assets/9d135088-d935-4366-8f71-eb7cb38448a9)





# RESULT:
The commands/batch files are executed successfully.

