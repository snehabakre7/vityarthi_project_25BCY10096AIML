# Problem Statement  
Managing library books manually often leads to issues such as misplaced records, incorrect availability status, and difficulty tracking which patron has borrowed which book.
This project solves these issues by creating a simple rule-based Library Management System using Prolog. It allows efficient tracking of books, patrons, borrowing activity, and book availability using logical facts and rules.

# Scope of the Project
1. Maintain a collection of books with details like title, author, and status.
2. Store information about library patrons.
3. Enable checking of book availability.
4. Allow patrons to borrow and return books.
5. Update book status dynamically using Prolog predicates.
6. Suitable for small library setups or academic demonstrations.

# Target Users
1. Students learning Prolog and logical programming
2. Small academic libraries
3. Teachers demonstrating rule-based expert systems
4. Beginners looking to understand dynamic knowledge bases
5. Anyone wanting a simple library tracking demo

# High-Level Features
1. Book Database: Stores book details and availability
2. Patron Database: Maintains user/patron list
3. Borrowing System: Updates book status and records who borrowed it
4. Returning System: Restores availability and removes borrowing record
5. Availability Check: Simple query to check if a book is free
6. Use of Dynamic Predicates: assert and retract used for real-time updates
