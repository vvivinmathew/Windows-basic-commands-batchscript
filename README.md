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
![img1](https://github.com/user-attachments/assets/35b27db7-08c0-4640-add6-ba992623e6a7)

Remove the directory "my-folder"

## COMMAND AND OUTPUT
![img2](https://github.com/user-attachments/assets/df456e08-f7f0-4b00-85b0-fdb54b64d183)

Create the file Rose.txt

## COMMAND AND OUTPUT
![Img3](https://github.com/user-attachments/assets/1997cc93-c353-4090-96c3-e796aae8df61)

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
![img4](https://github.com/user-attachments/assets/7e60aea1-6be7-488e-a823-668643b9d1fa)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![img5](https://github.com/user-attachments/assets/f75a8e9f-b129-4b10-b7cf-d43bef931044)
Remove the file hello1.txt

## COMMAND AND OUTPUT
![img6](https://github.com/user-attachments/assets/fb7cc9db-1d04-48d8-af3d-5505a92337ed)
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![img7](https://github.com/user-attachments/assets/aa903ab3-b731-4c9a-bd3f-96c3ae35ee1d)

List out all the associated file extensions 

## COMMAND AND OUTPUT
![img8](https://github.com/user-attachments/assets/a6b175a9-817b-4743-992d-2d26c346bc35)
![img9](https://github.com/user-attachments/assets/5b4bd0e0-495d-492a-9afc-c4f9da2a889e)
![img10](https://github.com/user-attachments/assets/6f3d126a-4d7a-42b7-87a1-3e40cd1adc11)
![img12](https://github.com/user-attachments/assets/f30f2b3c-2858-47df-bea5-05d5584891e2)
![img13](https://github.com/user-attachments/assets/67b016a1-010b-4c85-b550-c97ec1addb76)
![img14](https://github.com/user-attachments/assets/96f0d7ca-ac67-4284-bffd-bef41547cc1b)
![img15](https://github.com/user-attachments/assets/647812f3-80b1-4f54-a4c8-dfdd185a446b)
![img16](https://github.com/user-attachments/assets/ede27ce8-ed06-4ed5-94ab-a8cdffe8f18e)


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![img17](https://github.com/user-attachments/assets/a9685634-8ae7-4fee-bef3-cb1ff91ae83f)
## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
![img18](https://github.com/user-attachments/assets/04108d17-7736-4fe8-a679-2683667d6cc0)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![img19](https://github.com/user-attachments/assets/2068b4f1-f6b7-43fb-8466-2e92b6d69aaf)




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
![img20](https://github.com/user-attachments/assets/42cde7f6-aae8-4578-a1bd-39e20cb086fe)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

![img21](https://github.com/user-attachments/assets/f2f5d61a-6895-4fcc-b32d-bd80ae5024a6)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![img22](https://github.com/user-attachments/assets/8087696e-dcdb-414a-b2e0-c818b8f24d10)
# RESULT:
The commands/batch files are executed successfully.

