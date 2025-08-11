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

mkdir %userprofile%\Desktop\MyLab

<img width="707" height="51" alt="444061563-9115620f-1a86-4a2b-ae53-f0e1d26b359f" src="https://github.com/user-attachments/assets/0c9c9324-05cc-405c-955b-ff21302e1381" />

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT

cd %userprofile%\Desktop\MyLab

<img width="650" height="106" alt="444061887-ebd91539-0e28-43c6-9e87-ebb3f6e128c7" src="https://github.com/user-attachments/assets/652e58a3-0d0c-4860-bd09-21b8822040a3" />

type nul > MyFile.txt

<img width="650" height="106" alt="444061887-ebd91539-0e28-43c6-9e87-ebb3f6e128c7-1" src="https://github.com/user-attachments/assets/4f2d801c-ac83-4d66-aa6d-502f5ab2d1b3" />

List the contents of the "MyLab" directory.
## COMMAND AND OUTPUT

dir %userprofile%\Desktop\MyLab

<img width="815" height="321" alt="444062274-66e8c7bd-bab0-444c-8fd8-95fdcf3a71a6" src="https://github.com/user-attachments/assets/57e6e518-4128-4cf0-98ca-31fcda7e82bc" />

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\Backup

<img width="800" height="102" alt="444062361-1b776f5d-2080-4771-8ba4-bf3bbe7ac7e0" src="https://github.com/user-attachments/assets/0abac2fe-9d52-4dda-b889-acea67ef404a" />

copy MyFile.txt %userprofile%\Desktop\Backup

<img width="925" height="143" alt="444062622-85d89d2c-6fcb-496c-b7ac-b9a2793122ca" src="https://github.com/user-attachments/assets/7faa6ecb-4baa-4347-b1fa-f103ecc1b5ae" />

Move the "MyLab" directory to the "Documents" folder.
## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\Documents

<img width="891" height="223" alt="444062770-5a779f09-d4eb-499e-8476-7a7cb18015aa" src="https://github.com/user-attachments/assets/869e25bb-b507-4a17-9ba4-2496a1c771e7" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## COMMAND
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
## OUTPUT

<img width="957" height="247" alt="444063202-35d59cb9-4e09-468f-9c2a-78e990509a63" src="https://github.com/user-attachments/assets/b3d1eb64-6841-4bb7-9fdb-507bd853e37c" />


# RESULT:
The commands/batch files are executed successfully.

