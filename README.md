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
```
mkdir asgar
```
<img width="466" height="38" alt="image" src="https://github.com/user-attachments/assets/67a50ac5-11e6-4127-974f-f0b90dd3bce0" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
```
rmdir asgar
```
<img width="468" height="30" alt="image" src="https://github.com/user-attachments/assets/2a0fede1-3837-4779-9f44-03604fc66a8f" />


## COMMAND AND OUTPUT


Create the file Rose.txt
```
type nul > rose.txt
```
<img width="557" height="31" alt="image" src="https://github.com/user-attachments/assets/bd0dbd36-9021-4b04-bceb-b722e8cf8ad7" />



## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
```
echo Hello World > hello.txt
```
<img width="662" height="37" alt="image" src="https://github.com/user-attachments/assets/c935c8a4-66cb-492a-aef2-9a019840ea8f" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
```
copy hello.txt hello1.txt
```
<img width="642" height="52" alt="image" src="https://github.com/user-attachments/assets/42b1c44e-ce28-492f-8827-d1e315e6c2b3" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
```
del hello1.txt
```
<img width="502" height="31" alt="image" src="https://github.com/user-attachments/assets/6ab7d8f2-9d49-42ac-b316-02e52e78d48f" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
```
dir hello1.txt
```
<img width="533" height="167" alt="image" src="https://github.com/user-attachments/assets/6f4f33ec-5b78-47e5-8576-3b1def9c91c0" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
```
assoc
```
<img width="562" height="690" alt="image" src="https://github.com/user-attachments/assets/b33182f3-3dbe-493b-aa1e-4ca6348d5e01" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
```
fc hello.txt rose.txt
```
<img width="627" height="138" alt="image" src="https://github.com/user-attachments/assets/340dfa79-afe7-4d57-924b-c48c001a2344" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
```
@echo off
set name=John
echo Hello, %name%
pause
```




## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




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



# RESULT:
The commands/batch files are executed successfully.

