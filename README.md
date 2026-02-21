# Python Projects

A collection of Python projects built while learning programming.

---

## 1. Inventory Management System
**File:** `inventory_system.ipynb`

A command-line program that lets you manage a list of products. You can add items, view the full inventory, search for a specific item, update item details, delete items, sort by price, and filter by category. It also generates summary reports. All data is stored in memory, so it resets when the program closes.

**Built with:** Pure Python

---

## 2. Financial Tracker
**File:** `financial_tracker.ipynb`

A program that reads your bank statement (CSV file) and breaks down all incoming money. It shows your total received, splits transactions into categories (SIK, deposits, and other), lists every transaction from largest to smallest, and shows your top 10 biggest incoming payments.

**Built with:** Python, Pandas

> **Note:** To use this, export your bank statement as a CSV and update the `file_path` variable with the path to your file.

---

## 3. Library Management System
**File:** `library_management_system.ipynb`

A desktop app with a graphical interface for managing book borrowing at a library. You can add borrow records, view all borrowed books, search by student name or book title, and delete records. It automatically calculates fines for overdue books and highlights them in red. Data is saved to a local database so it persists between sessions.

**Built with:** Python, Tkinter, SQLite, tkcalendar

---

## Requirements

Install the required libraries by running:

```bash
pip install pandas tkcalendar
```

SQLite comes built into Python so no installation needed for that.
