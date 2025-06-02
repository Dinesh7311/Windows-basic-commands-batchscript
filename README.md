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
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/image.png)

Remove the directory "my-folder"

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20110611.png)

Create the file Rose.txt

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20110703.png)

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20110806.png)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20110957.png)

Remove the file hello1.txt

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20111101.png)

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20111101.png)

List out all the associated file extensions 

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20111128.png)

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20111225.png)

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-19%20111545.png)

## OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-27%20082440.png)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-27%20082759.png)


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-27%20082805.png)


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-27%20082947.png)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![](https://github.com/Mageshofficial2007/Windows-basic-commands-batchscript/raw/main/img/Screenshot%202025-05-27%20083108.png)


# RESULT:
The commands/batch files are executed successfully.
