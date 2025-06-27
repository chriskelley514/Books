Book Database Manager (C)

This is a simple console-based application written in C to manage a collection of books.

Features:
- Add new books with ID, title, and author
- Display all stored books
- Search for a book by ID
- Exit the program

How It Works:
- Uses an array of fixed size (100 books) to store book records in memory
- Provides a menu-driven interface for user interaction
- Searches linearly for books by ID

Requirements:
- Standard C compiler (gcc, clang, etc.)
- No external libraries required

Usage:
- Compile: gcc book_database.c -o book_database
- Run: ./book_database
- Follow on-screen menu prompts

Limitations:
- No file persistence; data is lost when program exits
- Fixed maximum number of books (100)
- Basic input validation

Potential Improvements:
- Add file storage for persistent data
- Use dynamic data structures for scalability
- Add more book details (year, genre, etc.)
- Implement update and delete functionality

Author: Christopher Kelley
License: MIT License
