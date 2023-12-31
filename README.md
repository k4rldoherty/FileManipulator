# FileManipulation
A java interview assesment practice question I worked on to sharpen my Java skills.

Problem Statement: File Search and Manipulation

You are tasked with creating a Java program that performs file search and manipulation. You need to implement the following functionalities:

File Search: Implement a method searchFiles(String directory, String extension) that searches for all files in the specified directory (and its subdirectories) with a given file extension (e.g., ".txt"). The method should return a list of file paths that match the criteria.

File Copy: Implement a method copyFile(String sourcePath, String destinationPath) that copies a file from the source path to the destination path. Ensure that the destination file does not overwrite an existing file with the same name.

File Deletion: Implement a method deleteFile(String filePath) that deletes a file specified by its path.

Menu System: Create a simple menu system that allows users to choose the operation they want to perform (search, copy, delete, recursive search), input the required parameters (e.g., file paths), and execute the chosen operation.

Error Handling: Handle potential exceptions that might occur during file operations, such as file not found, permission issues, etc. Display appropriate error messages to the user.

Version Control Integration: Create a new Git repository for your project and commit your code regularly with meaningful commit messages.

Ensure that your code is well-structured, follows object-oriented principles, and includes comments to explain your logic.

You can structure your program with a FileManipulator class that contains the methods mentioned above and a main method for interacting with the user through the menu system. 

Make sure to use exception handling to gracefully handle any potential errors during file operations.
