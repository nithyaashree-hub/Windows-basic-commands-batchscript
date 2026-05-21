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

<img width="427" height="50" alt="1" src="https://github.com/user-attachments/assets/cf9e216a-ee7c-413f-a82f-5327fda4acae" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="551" height="48" alt="2" src="https://github.com/user-attachments/assets/0500e258-35ff-45a3-a855-aac6d27a19ee" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="1174" height="365" alt="3" src="https://github.com/user-attachments/assets/6cc100ce-8fe5-4ee0-b12f-eb2d1b1cdffd" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="566" height="101" alt="4" src="https://github.com/user-attachments/assets/f25bb0a4-c23a-44a2-8c34-aefe9c99d391" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="676" height="124" alt="5" src="https://github.com/user-attachments/assets/dea18e28-1b07-401c-a0da-b15aa8657c9d" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="424" height="38" alt="6" src="https://github.com/user-attachments/assets/2f44a9f2-82b6-49c7-b44a-70bf6bf451df" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="1382" height="136" alt="7" src="https://github.com/user-attachments/assets/2bf5c37a-cf57-4e6d-acbb-034a5ac9829e" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="1920" height="1080" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/ad307cf4-0700-400b-9213-d442f71d75dc" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="1270" height="271" alt="8" src="https://github.com/user-attachments/assets/b23e8f49-5442-4a11-9596-1d025a3b83c2" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="1340" height="143" alt="9" src="https://github.com/user-attachments/assets/a559b94c-e7c9-4675-a9b2-b677320a254e" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="1920" height="278" alt="10" src="https://github.com/user-attachments/assets/b47879fa-a7dd-49ff-a75f-ae5a5fd4512f" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="1391" height="231" alt="11" src="https://github.com/user-attachments/assets/a93a4947-8c24-4c00-ba65-7f83d5d5eabc" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="975" height="284" alt="12" src="https://github.com/user-attachments/assets/aa206fba-e6bd-43e1-b409-31fe0885f8e7" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT

<img width="975" height="284" alt="12" src="https://github.com/user-attachments/assets/02e926fe-9db2-42dc-866a-03607f51b05b" />

# RESULT:
The commands/batch files are executed successfully.

