# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 



# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![383070830-f8f35e3e-256c-4e87-a4a3-d986a3a999a8](https://github.com/user-attachments/assets/24873fe5-ad30-4fb2-8bb4-f3a6b616fa96)


## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.

![383070688-7772ec41-df9c-413f-8bbd-2b8687553d13](https://github.com/user-attachments/assets/25d732df-a099-48fe-9ed2-b51758ba6db9)


## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![383070552-55532b80-746c-4b60-9b51-f85f58892dba](https://github.com/user-attachments/assets/03b93acf-3589-4ac8-8056-f4d5a71bfe0e)


## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.

![383070291-8510aa6b-0b31-4415-8a64-fef2e8fcb015](https://github.com/user-attachments/assets/52708057-68c1-42db-ab0d-a398e6d393be)


## COMMAND AND OUTPUT

![383070413-346a1cd7-6dd2-4635-9018-bdc6a67c9a1e](https://github.com/user-attachments/assets/1ffc3c13-ad6e-4af0-b3a2-273fc9d50259)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![383071423-50e4ff0e-115a-4d0d-bf2d-bc6a853b1136](https://github.com/user-attachments/assets/4f361c50-d79c-44f0-9dd1-51566ed190d1)



# RESULT:
The commands/batch files are executed successfully.

