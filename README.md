# Folder-Zipping-Program-
This program allows you to compress a folder into a .zip file. It optionally lets you specify a custom name for the zip file or uses the folder name by default.
Introduction
This program allows you to compress a folder into a .zip file. It optionally lets you specify a custom name for the zip file or uses the folder name by default.
Features
•	Compresses a specified folder into a .zip file.
•	Supports custom naming for the zip file.
•	Handles invalid folder paths and permission errors.
•	Ensures empty folders are included in the zip file. Requirements
•	Python 3.x
•	os and zipfile modules (included by default in Python) How to Use
1.	Run the Program: Start the program by running the script.
2.	Provide the Folder Path: When prompted, enter the path of the folder you want to zip. Ensure the path is correct.
3.	Optional Custom Name: The program will ask if you'd like to specify a custom name for the zip file. If you leave it blank, the folder name will be used as the zip file name.
4.	Zipping Process: The program will:
o	Check if the folder exists and is a valid directory.
o	Zip the contents of the folder, including any empty directories.
o	Save the .zip file in the same location as the folder. Error Handling
•	Invalid Folder Path: If the folder doesn't exist or the path is not a directory, the program will notify you.
•	Permission Issues: If there are permission errors, such as insufficient access rights, the program will show an error message.
•	Unexpected Errors: Any other issues during the zipping process will display an error message.
 
Example
If you have a folder named Documents and you don't specify a custom name, the program will create a file named Documents.zip containing all files and subfolders inside the Documents folder.
If you specify a custom name, for example, my_archive.zip, it will create the zip file with that name instead.
Code Explanation
1.	Check if the folder exists: It ensures that the provided path is valid and points to a folder.
2.	Zip the Folder: The program walks through the folder and adds all files and empty directories to the zip file.
3.	Handle Errors: It handles errors like permission issues and invalid paths. How to Run
1.	Save the script as assignment2.py.
2.	Open your terminal or command prompt.
3.	Run the script with the following command:
Copy code
python assignment2.py
4.	Enter the folder path and optional custom zip file name when prompted

