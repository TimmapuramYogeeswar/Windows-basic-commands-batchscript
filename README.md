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


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/b8facdb7-ef21-4228-a5f4-93afd716f1cf)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/9b97dcc1-e502-49cc-8df5-d553e823a222)
![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/574b4904-2bcb-49b9-b033-dd74ebc0c021)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/b5222a68-0763-48fb-b9b3-3ab0aefd298d)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
%userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/413f05c6-7ee1-485d-8a45-bb3469e9837c)

![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/244b858e-42c8-4972-b5c9-6573ed52099d)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents


![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/70ebad17-c1ac-4c64-a16a-ab387c87d35a)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT

![image](https://github.com/TimmapuramYogeeswar/Windows-basic-commands-batchscript/assets/154494746/c5184bd4-026b-4d9f-9a3e-91556d38024e)
# RESULT:
The commands/batch files are executed successfully.

