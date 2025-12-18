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
<img width="387" height="86" alt="8a" src="https://github.com/user-attachments/assets/2f461f93-7621-40b3-97c2-5260c850836a" />



Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="437" height="133" alt="8b" src="https://github.com/user-attachments/assets/52dab7ec-f296-4e36-b9fe-4900f536d9c5" />



Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="537" height="213" alt="8c" src="https://github.com/user-attachments/assets/dadc6184-3460-4f55-8f18-7f8b48e66f62" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="572" height="227" alt="8d" src="https://github.com/user-attachments/assets/904921e5-aeb5-437f-8ce9-691035322f4e" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="453" height="197" alt="8e" src="https://github.com/user-attachments/assets/aae6a496-89a8-489a-97ee-559bd8187e54" />


Remove the file hello1.txt
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="460" height="522" alt="8f" src="https://github.com/user-attachments/assets/98c659d2-4f4f-4a98-8e1a-6f32053bf43e" />



List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="468" height="192" alt="8g" src="https://github.com/user-attachments/assets/3bf1a561-e25c-4866-9661-48db028002fc" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="347" height="130" alt="8h" src="https://github.com/user-attachments/assets/94fa1b12-d38e-4623-b513-9d3cd05b6e63" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="488" height="276" alt="8i" src="https://github.com/user-attachments/assets/2457c66c-d94b-4664-87e2-624c59908064" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="400" height="287" alt="8j" src="https://github.com/user-attachments/assets/5f9e9109-de67-43a2-b701-c7f808882160" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="381" height="198" alt="8k" src="https://github.com/user-attachments/assets/a978369d-3439-45b1-ac51-1d1f36c3d34c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="352" height="370" alt="8l" src="https://github.com/user-attachments/assets/15c1e0f9-093c-4377-a441-bdcef27eea90" />



# RESULT:
The commands/batch files are executed successfully.

