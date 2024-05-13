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
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/6e82a26c-37ec-430a-b08e-6d58dcd7def7)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/19b0ac83-e340-47de-9d66-fe6dbe853055)
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/c1c08ce1-9dbe-4695-8a99-3339d23923c0)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/c9a157b5-102b-4ce7-9166-f87df80edfd5)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/4acfdc6a-bc17-4210-b89e-87285726edd1)
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/289eb42a-80ff-41be-9427-e48c01bb601e)



## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/1a343fc6-6a6d-48ff-819a-a836e18181e5)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!





## OUTPUT
![image](https://github.com/Ritika-2706/Windows-basic-commands-batchscript/assets/93427238/d8a28e2d-d593-402c-99c3-bc7276da138b)





# RESULT:
The commands/batch files are executed successfully.

