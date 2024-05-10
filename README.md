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

~~~
mkdir %userprofile%\Desktop\MyLab
~~~
![326683013-f1f83410-e659-40ff-bee3-e079d93c7736](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/398612b3-9655-420e-a9c9-f200a24d5232)

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![326153283-dad40a0f-95e6-4dc5-b79f-f079be18a517](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/56ead55b-3ebc-457a-9b66-9e794536ea8d)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

~~~
cd %userprofile%\Desktop\MyLab
~~~
![326683213-4de1b4bd-f842-485a-bf0d-90def6eaf1e9](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/d1900a0b-4c3c-4770-bafa-39161e0a2c1c)

![326683200-60ef83ad-950a-4bf7-ae70-7ccd4fae7aa7](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/bffe5243-b728-440c-af14-be8e5105bab9)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

~~~
dir %userprofile%\Desktop\MyLab
~~~
![326683303-a28afee5-4fc8-4720-a29b-ae4c9819f177](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/ed4e8f45-9c2b-4c9a-9220-63bd3cfe0baa)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

~~~
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
~~~
![326683342-ad0e4f9e-575b-48f5-95fe-7df3f52b5857](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/a71f24b7-e9c4-40c6-a824-55f3466b4095)

![326683348-fc1a73ef-f263-4896-9465-239e1420b390](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/6b368260-d83c-4bb4-bdb8-8fd0601a9dd7)

## COMMAND AND OUTPUT

~~~
mv Myfile.txt %userprofile%\Documents
~~~
![326683386-0fe73689-4d9b-4494-8ce8-d940fc9b9606](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/49dd374a-73a4-47f1-946f-86963b81a5b6)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
~~~
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
~~~

Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
~~~
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
~~~
![326683409-f8257a6d-6fa4-4e1a-bc73-063fad3c5508](https://github.com/04Varsha/Windows-basic-commands-batchscript/assets/149035374/e6f191cf-508d-4d3e-91da-9b9c27b9ab4c)





## OUTPUT





# RESULT:
The commands/batch files are executed successfully.


