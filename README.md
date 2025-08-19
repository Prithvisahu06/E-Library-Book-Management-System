# E-Library Book Management System 📚

A command-line based E-Library Management System built with Python. This project demonstrates the use of fundamental data structures to manage a digital book inventory, allowing users to add, borrow, return, and search for books.

---

## ✨ Key Features

* **Add Books**: Easily add new books to the library's inventory.
* **Borrow & Return**: Manage the status of books by borrowing and returning them.
* **Undo Last Action**: Made a mistake? The system uses a stack to allow you to undo the last borrow or return action.
* **Search/Filter**: Quickly find books by searching for keywords in their title or author's name.
* **Display Inventory**: View a complete list of all books in the library and their current availability status.

---

## 🧠 Data Structures Used

This project is a practical implementation of two core data structures:

* **Linked List**: The entire book inventory is managed using a custom-built Linked List. This structure efficiently handles the dynamic addition of new books.
* **Stack**: The "Undo" feature is powered by a Stack. Every time a book is borrowed or returned, the action is pushed onto the stack, allowing the last operation to be easily reversed.

---

## 🚀 How to Use

1.  **Prerequisites**: Ensure you have Python 3 installed.
2.  **Run the Script**: Execute the Python file directly from your terminal:
    ```bash
    python your_script_name.py
    ```
3.  **View the Output**: The script will run through a pre-defined set of example operations (adding, borrowing, returning, undoing, and searching) and print the results to the console.

---

## 🛠️ Built With

* **Python 3** (No external libraries required)

