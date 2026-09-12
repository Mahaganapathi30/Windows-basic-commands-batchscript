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
<img width="406" height="43" alt="image" src="https://github.com/user-attachments/assets/6fad62d0-e5d0-42ea-829d-e1428f8aa96f" />

Remove the directory "my-folder"
## COMMAND AND OUTPUT
<img width="385" height="50" alt="image" src="https://github.com/user-attachments/assets/07566c91-eff8-4823-8305-9807397cfb90" />

Create the file Rose.txt
## COMMAND AND OUTPUT
<img width="623" height="388" alt="image" src="https://github.com/user-attachments/assets/b4e946fc-fca1-4bfa-af8c-8189d61f4c69" />

Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
<img width="566" height="108" alt="image" src="https://github.com/user-attachments/assets/0cd4dae4-5042-4103-8d5c-80d5165201bc" />

Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
<img width="538" height="71" alt="image" src="https://github.com/user-attachments/assets/1e04c5c1-694a-4ea8-b938-f768b6066608" />

Remove the file hello1.txt
## COMMAND AND OUTPUT
<img width="384" height="27" alt="image" src="https://github.com/user-attachments/assets/6ba01681-52d3-483f-8a20-9bc49142a0c1" />

List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
<img width="473" height="178" alt="image" src="https://github.com/user-attachments/assets/1145ffc6-8d59-4b3c-97c4-725c63b3a1cd" />

List out all the associated file extensions 
## COMMAND AND OUTPUT
<img width="467" height="283" alt="image" src="https://github.com/user-attachments/assets/cd96e608-2298-401b-a1ba-b4586a8ffc1b" />

Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
<img width="526" height="215" alt="image" src="https://github.com/user-attachments/assets/272c1f2c-7ba5-4a5c-8532-d8dbfdcef693" />


## Exercise 2: Advanced Batch Scripting

Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT:
<img width="447" height="134" alt="image" src="https://github.com/user-attachments/assets/6a17bfa6-eced-47f7-931d-9970b7fb1834" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT:
<img width="580" height="266" alt="image" src="https://github.com/user-attachments/assets/fadce236-45a3-4477-8a5b-9076507f68d6" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT:
<img width="384" height="167" alt="image" src="https://github.com/user-attachments/assets/97da85d5-0a6b-4917-acfb-d3d0e0a49246" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="571" height="238" alt="image" src="https://github.com/user-attachments/assets/12bafabe-5a19-4986-b445-fd7cedf29fa7" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="397" height="400" alt="image" src="https://github.com/user-attachments/assets/0abddac1-12ef-4d6b-b406-071c90b411d3" />

# RESULT:
The commands/batch files are executed successfully.

