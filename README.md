# Bookshop Management System

This is a Bookshop Management System written in C++. It provides functionalities to manage books, suppliers, purchases, employees, members, and sales for a bookshop.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Main Menu](#main-menu)
  - [Book Menu](#book-menu)
  - [Supplier Menu](#supplier-menu)
  - [Purchases Menu](#purchases-menu)
  - [Employee Menu](#employee-menu)
  - [Member Menu](#member-menu)
  - [Sales Menu](#sales-menu)
- [Contributing](#contributing)

## Features

- Add, update, and search for books
- Manage suppliers: add, remove, and search
- Handle purchase orders: create, view, mark as received, and cancel
- Employee management: add, search, assign manager status, update salary, and view
- Member management: add, search, and view
- Sales: generate bills, track total sales for the year

## Getting Started

### Prerequisites

- C++ compiler
- MySQL database
- MySQL Connector for C++

### Installation

1. Clone the repository:

   git clone https://github.com/rajanarahul93/Book-Management-System.git


2. Compile the code using a C++ compiler.

3. Ensure that the MySQL Connector for C++ is properly set up and configured.

## Usage

### Main Menu

The main menu provides options to navigate to different modules of the system, such as books, suppliers, purchases, employees, members, and sales.

### Book Menu

- *Add Book:* Add a new book to the inventory.
- *Update Price:* Update the price of a book.
- *Search Book:* Search for details of a specific book.
- *Update Status:* Update the status of books based on received orders.
- *Display All:* Display details of all books in the inventory.

### Supplier Menu

- **Add Supplier:** Add a new supplier to the system.
- **Remove Supplier:** Remove a supplier from the system.
- **Search Supplier:** Search for details of a specific supplier.

### Purchases Menu

- **New Order:** Place a new order for books.
- **View All:** View all purchase orders based on different criteria.
- **Cancel Order:** Cancel a placed order.
- **Mark Received:** Mark an order as received.

### Employee Menu

- **New Employee:** Add a new employee to the system.
- **Search Employee:** Search for details of a specific employee.
- **Assign Manager Status:** Assign manager status to an employee.
- **View All:** Display details of all employees.
- **Update Salary:** Update the salary of an employee.

### Member Menu

- **New Member:** Add a new member to the system.
- **Search Member:** Search for details of a specific member.

### Sales Menu

- **Add New Bill:** Generate a new bill for a member's purchase.
- **Total Sales of the Year:** View the total sales for the current year.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

