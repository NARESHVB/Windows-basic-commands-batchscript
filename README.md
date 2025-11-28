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
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="1271" height="317" alt="image" src="https://github.com/user-attachments/assets/33b7ed28-0d86-4425-8ea4-7ee10ce7f537" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="1206" height="289" alt="image" src="https://github.com/user-attachments/assets/bbeba363-fe9a-404f-ab1d-601b0b185a01" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="348" height="149" alt="image" src="https://github.com/user-attachments/assets/79269edd-eaab-446a-bd51-0d11e74b7ebf" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="406" height="123" alt="image" src="https://github.com/user-attachments/assets/35a55d7a-0bde-4067-ba1f-2065c83245b9" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="354" height="105" alt="image" src="https://github.com/user-attachments/assets/ccf12fff-c9ba-45fc-89e2-d2a6b1753f76" />


Remove the file hello1.txt
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="339" height="118" alt="image" src="https://github.com/user-attachments/assets/504fde4d-aca2-44f3-857b-19f7e645de1c" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="598" height="150" alt="image" src="https://github.com/user-attachments/assets/cf59fc09-2b0c-41ab-b858-6cc4d3ca84bb" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="396" height="198" alt="image" src="https://github.com/user-attachments/assets/e6874f26-c8de-4d29-864b-0f3429753970" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="662" height="442" alt="image" src="https://github.com/user-attachments/assets/ed8140ac-bd45-4c89-9373-76e02f274def" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="526" height="355" alt="image" src="https://github.com/user-attachments/assets/08ca5d8e-cc61-4b6f-93c6-06b8435ff3d8" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="383" height="277" alt="image" src="https://github.com/user-attachments/assets/5356eb38-a2da-43e0-8f94-90f1683a0b1c" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="361" height="287" alt="image" src="https://github.com/user-attachments/assets/4e976aef-d566-4015-b21f-d842f795aaa0" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="401" height="331" alt="image" src="https://github.com/user-attachments/assets/3fdfc531-dfd7-4b5c-8817-be5f085fd11e" />



# RESULT:
The commands/batch files are executed successfully.

