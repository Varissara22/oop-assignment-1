# Library management system

This is a basic Python project that demonstrates object-oriented programming (OOP) whcich evelop from procedral code.

---

## Features

This work has 3 has classes: Book class, Member class, Library class.

The **Book** class supports the following attributes:

- `id`: Unique identifier for the book
- `title`: Book title
- `author`: Book author
- `total_copies`: Total number of copies owned by the library
- `available_copies`: Number of copies currently available for borrowing

The **Member** class supports the following attributes:

- `id:` Unique identifier for the member
- `name:` Member's name
- `email:` Member's email address
- `borrowed_books_list:` List of book IDs currently borrowed by the member

The **Library** class supports the following operations:
- `add_book(book_id, title, author, available_copies):` Add a new book to the library
- `add_member(member_id, name, email):` Register a new member
- `borrow_book(member_id, book_id):` Process a book checkout
- `return_book(member_id, book_id):` Process a book return
- `display_available_books():` Show all books with available copies
- `display_member_books(member_id):` Show books borrowed by a specific member

---

## Business Rules

- `Borrowing Limit:` Each member can borrow a maximum of 3 books at a time
- `Availability Check:` Books can only be borrowed if copies are available
- `Valid Transactions:` Only registered members can borrow books
- `Return Validation:` Members can only return books they have actually borrowed

---

## Error Handling

The system provides clear error messages for:
- Member not found
- Book not found
- No copies available
- Borrowing limit reached
- Invalid return attempts

---

## Requirements

* Python 3.x

---

##  How to Use

To run the demonstration script, run in `test_oop.py` file.