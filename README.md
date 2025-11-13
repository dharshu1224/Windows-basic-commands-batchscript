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

<img width="379" height="53" alt="image" src="https://github.com/user-attachments/assets/e999d344-f9a2-43e7-a641-23ad378ba18d" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="406" height="85" alt="image" src="https://github.com/user-attachments/assets/5e35b06c-1414-4246-9861-ac3adfe559a1" />


## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="650" height="272" alt="image" src="https://github.com/user-attachments/assets/8c0dd4c1-57fa-4be1-937b-45584523cc28" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="562" height="124" alt="image" src="https://github.com/user-attachments/assets/dbfbcc34-37ee-4528-9a94-3f5edaf6710f" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="509" height="127" alt="image" src="https://github.com/user-attachments/assets/0b38e07c-4a72-45f0-b8b7-6d5c133100aa" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="376" height="63" alt="image" src="https://github.com/user-attachments/assets/717b2963-d8fe-4fdf-b57f-d86f440c0ad0" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="441" height="201" alt="image" src="https://github.com/user-attachments/assets/ca00144e-4c0f-4921-b2cd-d9445bde7a2f" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="588" height="270" alt="image" src="https://github.com/user-attachments/assets/63629f8d-a5df-4bde-8565-bac4651dbc0e" />


## COMMAND AND OUTPUT

<img width="588" height="270" alt="image" src="https://github.com/user-attachments/assets/63629f8d-a5df-4bde-8565-bac4651dbc0e" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="417" height="140" alt="image" src="https://github.com/user-attachments/assets/8765bcc3-342a-4bfb-b6b4-bbba5a7613b6" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="590" height="418" alt="image" src="https://github.com/user-attachments/assets/8f84ce49-4ce9-4d05-800f-8fad19a79624" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="409" height="238" alt="image" src="https://github.com/user-attachments/assets/9c07c5c6-559c-40ff-b1da-7f73f76cecdb" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="601" height="281" alt="image" src="https://github.com/user-attachments/assets/b19454ac-e9e4-482a-8a94-d8a6374b1981" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="461" height="424" alt="image" src="https://github.com/user-attachments/assets/03f94b5a-4607-4568-8404-1ae9ece6cd8f" />




# RESULT:
The commands/batch files are executed successfully.

