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

<img width="387" height="86" alt="8a" src="https://github.com/user-attachments/assets/ff62e9be-6ed4-4808-a3da-c5deaf9a88c2" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="437" height="133" alt="8b" src="https://github.com/user-attachments/assets/3f57a490-87ed-4dbc-946a-7b4f103d4cdc" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="537" height="213" alt="8c" src="https://github.com/user-attachments/assets/edfd726f-60ba-419a-8897-b58f8a52db0f" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="572" height="227" alt="8d" src="https://github.com/user-attachments/assets/20d615b1-433f-4078-a4b1-53d1b9226d1e" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="453" height="197" alt="8e" src="https://github.com/user-attachments/assets/d5b5bcdf-d171-4108-974e-cb22795efdd2" />


Remove the file hello1.txt
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="460" height="522" alt="8f" src="https://github.com/user-attachments/assets/2cea4223-175b-46e4-8660-c8e949f728d9" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="468" height="192" alt="8g" src="https://github.com/user-attachments/assets/500e284d-b6e0-4a36-814a-c38470a69c66" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="347" height="130" alt="8h" src="https://github.com/user-attachments/assets/1f5a4a6a-a5e2-44f5-9374-9e85e0ae6953" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT


<img width="488" height="276" alt="8i" src="https://github.com/user-attachments/assets/063f3671-9a5f-4fb0-a794-edf3c29f97a8" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="400" height="287" alt="8j" src="https://github.com/user-attachments/assets/2d8ff591-ac5c-4bc7-bd13-d5ddf0be2ab2" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="381" height="198" alt="8k" src="https://github.com/user-attachments/assets/2dbc4ae8-b815-4bd8-bc20-bf1a6305821a" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="352" height="370" alt="8l" src="https://github.com/user-attachments/assets/9083f42b-3be2-4edc-8f04-ee9c3218e53a" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


# RESULT:
The commands/batch files are executed successfully.

