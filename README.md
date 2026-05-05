# FILE-HANDLING-UTILITY

COMPANY: CODTECH IT SOLUTIONS

NAME: KHEDEKAR PRATHAMESH SUNIL

INTERN ID: CTIS9258

DOMAIN: JAVA

DURATION: 4 WEEKS

MENTOR:NEELA SANTOSH

This program is a menu-driven File Handling Utility in Java that demonstrates the implementation of basic and intermediate file operations in a structured and interactive manner. It allows users to perform essential tasks such as creating a file, writing data into it, reading its content, modifying existing data, and viewing file information. The program uses a console-based interface, making it easy for beginners to understand how file handling works in real-world Java applications.

At the beginning, the program imports two important Java packages: java.io.* and java.util.*. The java.io package provides classes required for file input and output operations, while java.util.Scanner is used to take input from the user. A global variable fileName is defined as "Example.txt", which is the file on which all operations are performed. A Scanner object is created to continuously accept user input throughout the program.

The main() method is the central part of the program. It runs an infinite loop using while(true) to repeatedly display a menu until the user decides to exit. The menu includes six options: create a file, write to a file, read a file, modify a file, display file information, and exit the program. Based on the user’s choice, a switch-case structure is used to call the respective method. Exception handling using try-catch is included to handle IOException, ensuring that the program runs smoothly even if file errors occur.

The createFile() method is used to create a new file using the File class in Java. It checks whether the file already exists using the createNewFile() method. If the file does not exist, it is created successfully and a confirmation message is displayed. If it already exists, the program informs the user that no new file is created. This prevents duplication and accidental overwriting.

The writeFile() method allows the user to write data into the file. The user enters text and is also asked whether they want append mode. If the user selects “yes,” new data is added at the end of the file; otherwise, existing content is overwritten. This is implemented using the FileWriter class with an append flag, making the method flexible for both writing and updating purposes.

The readFile() method reads and displays the file content line by line using BufferedReader and FileReader. Before reading, it checks if the file exists. If it does not exist, an error message is shown. Otherwise, the entire content is displayed neatly on the console.

The modifyFile() method is used to update existing content in the file. It first reads all data into a StringBuilder. The user is then asked to enter a word they want to replace and the new word. The program uses the replace() method to modify the text and writes the updated content back into the file, replacing the previous version.

The showFileInfo() method displays basic file details such as file name, absolute path, and file size in bytes. This helps users understand file properties without manually opening it.

Overall, this program demonstrates practical file handling in Java, including creation, reading, writing, modification, and file metadata retrieval. It also strengthens understanding of loops, conditional statements, exception handling, and object-oriented programming concepts, making it a useful beginner-level project for learning file management in Java.
