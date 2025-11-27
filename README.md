# vityarthi_project_25BCY10096AIML  
Project Overview  
This project is a simple Library Management System built using Prolog.
It allows users to store book information, manage library patrons, check availability, borrow books, and return books.  
The project demonstrates the use of facts, rules, and dynamic updates (assert and retract) in Prolog.  
  Features
1. Add and store books in the library  
2. Store patron (member) information  
3. Check if a book is available  
4. Borrow a book (updates book status + records patron)  
5. Return a book (restores availability)  
6. Simple rule-based logic for all operations

Technologies / Tools Used  
1. Prolog (SWI-Prolog recommended)
2. Basic text editor / IDE (VS Code, Sublime, Notepad++, etc.)

Steps to Install & Run the Project  
1. Install SWI-Prolog.
2. Save the code.
3. Load the file.
4. Run any queries like:-
borrow('The Hobbit', 'Charlie').
return('1984', 'Bob').
is_available('1984').
