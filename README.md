Line Editor in C++
Project Overview
The Line Editor is a command-line program built in C++ that allows users to read, edit, and write text files with functionalities like adding, updating, deleting lines, searching for words, and undo/redo operations. This program demonstrates the use of dynamic memory management, file I/O, and data structure manipulation to build a practical utility tool.

Features
File Operations

Open an existing text file or create a new one if the file does not exist.
Save changes to the file after editing.
Buffer Management

Load up to 25 lines of text into a buffer for manipulation.
Dynamically allocate and manage memory for text storage.
CRUD Operations

Add a line at a specific position in the buffer.
Update an existing line.
Delete a line from the buffer.
Search Functionality

Search for a specific word in the text.
Display the line number and content where the word is found.
Undo/Redo

Undo the last three operations (add, delete, or update).
Redo the last three undone operations.
Interactive Menu

User-friendly menu-driven interface for performing actions.
