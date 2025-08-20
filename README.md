# E-Library Book Management System 

A command-line E-Library Management System developed using Python. The project illustrates the application of basic data structures for handling an electronic book collection where users can add, borrow, return, and search for books.

---

## Key Features

* **Add Books**:Quickly add new books to the library's collection.
* **Borrow & Return**: Handle the availability of books by borrowing and returning them.
* **Undo Last Action**:Did you make a mistake? The system utilizes a stack in order to let you undo the last return or borrow action.
* **Search/Filter**: Get to books quickly by searching for keywords in the title or author name.
* **Display Inventory**:  See a list of all the books in the library and their availability status.

---

## Data Structures That Are Used

This project is a real-world example of two fundamental data structures:

* **Linked List**: The whole book catalog is handled using a self-made Linked List. This data structure effectively deals with the dynamic insertion of new books.
* **Stack**:  The "Undo" functionality is driven by a Stack. Each time a book is borrowed or returned, the operation is pushed onto the stack, making it possible to reverse the previous action with ease.
---

### How to Use

1.  **Prerequisites**: Make sure you have Python 3 installed.
2.  **Run the Script**: Simply run the Python script directly from your command line:
    ```bash
    python your_script_name.py
    ```
3.  **See the Output**: The script will iterate over a predefined list of sample operations (adding, borrowing, returning, undoing, and searching) and output the results to the console.
---

## Built With

* **Python 3** (No external libraries needed)

