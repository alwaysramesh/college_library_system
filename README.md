Project Description:

This is a simple Python program that simulates the operations of a college library system. It uses two classes: Library and Student.

Library Class:

The Library class has three main methods:
__init__(self, listOfBooks): Initializes the library with a list of books.
displayAvailableBooks(): Displays all the available books in the library.
borrowBook(bookName): Allows a student to borrow a book if it is available. If the book is already borrowed, the method will notify the student that the book is unavailable.
returnBook(bookName): Allows a student to return a book back to the library.
Student Class:

The Student class has two methods:
requestBook(): Prompts the student to input the name of the book they want to borrow.
returnBook(): Prompts the student to input the name of the book they want to return.
Main Program:

In the main program, an instance of Library is created with a list of books: "Clean Code", "The Pragmatic Programmer", "Designing Data-Intensive Applications", and "Python Notes".
The user is presented with a menu that allows them to:
List all available books in the library.
Request to borrow a book.
Return a book to the library.
Exit the system.
Based on the user’s input, the appropriate function is called to either display books, borrow a book, return a book, or exit the program.
