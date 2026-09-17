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
<img width="642" height="231" alt="Screenshot 2026-09-01 160856" src="https://github.com/user-attachments/assets/39b2b76b-e6d6-405d-8f8e-1a3140765772" />


## COMMAND AND OUTPUT
Remove the directory "my-folder"
<img width="720" height="107" alt="Screenshot 2026-09-01 161204" src="https://github.com/user-attachments/assets/4ec0df27-4d4b-477b-9742-2ea17f12f33c" />


## COMMAND AND OUTPUT

<img width="704" height="195" alt="Screenshot 2026-09-01 161212" src="https://github.com/user-attachments/assets/103d6391-67b8-4a9e-b21e-094c417aa9cf" />
<img width="785" height="228" alt="Screenshot 2026-09-01 161221" src="https://github.com/user-attachments/assets/2dea9a05-a23c-4e40-b439-d6c5eea2aed4" />
Create the file Rose.txt


## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="657" height="115" alt="Screenshot 2026-09-01 161234" src="https://github.com/user-attachments/assets/e7c6b2cc-751b-42d0-83aa-ddbbd6fed36a" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="657" height="115" alt="Screenshot 2026-09-01 161234" src="https://github.com/user-attachments/assets/33452fb9-ee92-4010-a1da-5046e88edde2" />



## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="637" height="160" alt="Screenshot 2026-09-01 161259" src="https://github.com/user-attachments/assets/94b1b621-5907-40ff-9ca2-783f4cab0280" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="768" height="240" alt="Screenshot 2026-09-01 161405" src="https://github.com/user-attachments/assets/1c65c24a-b705-4604-8d46-d746d8fd70a1" />


## COMMAND AND OUTPUT
List out all the associated file extensions 
<img width="777" height="543" alt="Screenshot 2026-09-01 161433" src="https://github.com/user-attachments/assets/f863bdfa-4430-4686-aced-80a00a18aabe" />


## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="702" height="265" alt="Screenshot 2026-09-01 161501" src="https://github.com/user-attachments/assets/c50893e4-0caa-4130-8a01-374b68fad797" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="632" height="155" alt="Screenshot 2026-09-01 161620" src="https://github.com/user-attachments/assets/94b160b0-ce92-4b51-8592-0512baf1b53c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="776" height="292" alt="Screenshot 2026-09-05 192058" src="https://github.com/user-attachments/assets/2f60ced1-741f-442d-bd4e-76b477f97c64" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT
<img width="692" height="240" alt="Screenshot 2026-09-05 192153" src="https://github.com/user-attachments/assets/28f8f18e-4f13-4911-9755-ec23c5af651b" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="801" height="257" alt="Screenshot 2026-09-05 192324" src="https://github.com/user-attachments/assets/07a2ebb9-014a-4f5c-acdb-af91cc0d213f" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="805" height="447" alt="Screenshot 2026-09-05 192445" src="https://github.com/user-attachments/assets/e2378570-19c9-4ded-b61f-d7c21a10d421" />


# RESULT:
The commands/batch files are executed successfully.

