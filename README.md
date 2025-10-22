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

<img width="401" height="32" alt="Screenshot 2025-10-22 093457" src="https://github.com/user-attachments/assets/1e0e0231-3a8b-42b9-a335-7493d67aa3d6" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="467" height="47" alt="Screenshot 2025-10-22 093609" src="https://github.com/user-attachments/assets/7b8c36cf-8020-4832-8c2f-7bd7f04aa7ae" />



## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="655" height="154" alt="Screenshot 2025-10-22 093648" src="https://github.com/user-attachments/assets/b807a439-9259-43c7-a409-2b07e4ea832e" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="539" height="39" alt="Screenshot 2025-10-22 093706" src="https://github.com/user-attachments/assets/3a4c1c4d-78cc-40c8-95a4-58068c71111d" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="504" height="61" alt="Screenshot 2025-10-22 093713" src="https://github.com/user-attachments/assets/b2ff7fd7-2d63-40ad-b233-40c4116bf74b" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="372" height="47" alt="Screenshot 2025-10-22 093728" src="https://github.com/user-attachments/assets/c5a82f79-4038-493c-81a5-d8125f42cef6" />



## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="645" height="180" alt="Screenshot 2025-10-22 093736" src="https://github.com/user-attachments/assets/028d241e-bb9d-4bdc-b7ed-9d3928d75649" />



## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="542" height="907" alt="Screenshot 2025-10-22 093810" src="https://github.com/user-attachments/assets/a612ca92-9dd8-43b6-bb38-c5924d434fca" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="541" height="157" alt="Screenshot 2025-10-22 093825" src="https://github.com/user-attachments/assets/16a27e4f-2832-40bb-98c5-26fd0bcfe359" />



## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting

Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="446" height="88" alt="Screenshot 2025-10-22 095431" src="https://github.com/user-attachments/assets/61f3f2eb-bed8-497c-9518-c9a37d2fd13a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="624" height="197" alt="Screenshot 2025-10-22 095451" src="https://github.com/user-attachments/assets/528163ae-2675-4b55-9bbb-f42fdb9c8c9d" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


## OUTPUT

<img width="419" height="290" alt="Screenshot 2025-10-22 095229" src="https://github.com/user-attachments/assets/6a782e16-d6e9-4384-92c7-ce3483e88dcf" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):


## OUTPUT

<img width="438" height="219" alt="Screenshot 2025-10-22 095332" src="https://github.com/user-attachments/assets/41339aa8-79c9-46da-99a9-5a0e341c548e" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="431" height="200" alt="Screenshot 2025-10-22 095417" src="https://github.com/user-attachments/assets/38c14381-4cfa-4c6b-9522-af1d07e8f0f0" />


# RESULT:
The commands/batch files are executed successfully.

