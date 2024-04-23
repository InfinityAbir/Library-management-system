# Library-management-system
A project by php, css, html.
# CRUD Application using PHP, MySQL, HTML, and CSS

This project demonstrates a simple CRUD application built with PHP, MySQL, HTML, and CSS. CRUD operations refer to Create, Read, Update, and Delete actions performed on a database.

## Getting Started

### Prerequisites

Before starting, ensure you have the following:

- Apache server with PHP support installed
- MySQL server installed
- Basic understanding of PHP, MySQL, HTML, and CSS

### Setting Up the Database

1. Create a new database named `crud`.
2. Create a table named `books` with the following structure:

```sql
CREATE TABLE books (
    id INT(6) AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(191) NOT NULL,
    author VARCHAR(191) NOT NULL,
    type VARCHAR(191) NOT NULL,
    description VARCHAR(191) NOT NULL
);
