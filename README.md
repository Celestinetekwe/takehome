# Take Home Project

Challenge: A directory contains multiple files and directories of non-uniform file and directory names. Create a program that traverses a base directory and creates an index file that can be used to quickly lookup files by name, size, and content type.

# Instructions

Fork this repository and implement the above requirements. The result must be an application that implements both the index and search features. Use your best judgement as to the interface that is used to use the index and search features, but remember that this is meant to create a dialog during the interview process, not be something that would be used in production.

Feel free to use the language, libraries, and tools that you are most comfortable in and best reflect your ability to translate requirements into a functional implementation.

Once the project is implemented, remove the `# Instructions` section of this readme and add the section `# Usage` with instructions on how to run the produced application.

The `test_data` directory in this project contains files and directories that can be used to test your implementation.

Good luck.

# Usage
To run the application, you need to have Python installed on your system. Follow the steps below to set up and run the program:

Clone the repository to your local machine.

Navigate to the project directory:

cd /path/to/project

Run the program with the following command:
python file_indexer.py
This command will start the application and display the main menu.

Application Instructions
The application provides a simple command-line interface to index files and perform searches. The following options are available:

Index a Directory
Search Files
Exit
To use the application, follow these steps:

Choose the Index a Directory option to create an index for a directory. Enter the base directory path when prompted.

The program will recursively traverse the directory and create an index file.

Once the indexing is complete, you will be returned to the main menu.

Choose the Search Files option to perform a search. Enter the search query when prompted.

The program will search for files matching the query and display the results.

Choose the Exit option to exit the application.

That's it! You can use the file indexer application to index directories and search for files based on name, size, and content type.
Note: Make sure you have the mimetypes module installed. If not, you can install it using pip install mimetypes.