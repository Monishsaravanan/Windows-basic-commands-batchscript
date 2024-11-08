# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

NAME : MONISH S

REG NO : 212223040115

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


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/8dfa09dc-9cf3-41f0-b817-e5ac65a41898)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/45e31376-6f90-44de-817a-ba27e860383e)

List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/5240c900-c8df-47b2-9e54-0280de8c45d5)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/617d13a3-3464-4cbb-8a72-de995ab79560)

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/8eebfc9b-0833-49f1-a952-fcfcea899672)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!

```

## OUTPUT
![image](https://github.com/user-attachments/assets/1c85761c-c20a-44a8-ae2c-f4d62e49c1ea)


# RESULT:
The commands/batch files are executed successfully.

