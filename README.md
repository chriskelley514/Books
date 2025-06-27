# Books
Book Management System 

This is a simple terminal-based book management system written in C. It allows users to add books, view all stored books, and search for a book by its ID. The program uses a fixed-size array and basic input handling to manage the data.

Features:
Add a book with ID, title, and author

Display all books currently in the database

Search for a book by its unique ID

Graceful input handling and menu interface

How It Works:
Books are stored in a Book struct array of fixed size (MAX_BOOKS = 100). Each book has:

id: An integer identifier

title: A string (up to 49 characters)

author: A string (up to 49 characters)

The main loop presents a simple menu with options to:

Add a book

Display all books

Search a book by ID

Exit the program

How to Compile:
To compile the program, use gcc:

bash
gcc -o book_manager book_manager.c

Then run:
bash
./book_manager

Example Usage:
mathematica
1. Add Book
2. Display Books
3. Search Book by ID
4. Exit
Enter choice: 1
Enter book ID: 101
Enter book title: The C Programming Language
Enter author name: Kernighan and Ritchie
Book added successfully.

Enter choice: 2
Books in database:
101: The C Programming Language by Kernighan and Ritchie

Enter choice: 3
Enter the ID of the book to search: 101
Book Found:
ID: 101
Title: The C Programming Language
Author: Kernighan and Ritchie

Limitations:
Book storage is limited to 100 entries.

Data is stored only in memory; exiting the program clears all entries.

IDs must be entered manually and are not auto-generated or checked for duplicates.

License:
This project is open source and free to use under the MIT License.
