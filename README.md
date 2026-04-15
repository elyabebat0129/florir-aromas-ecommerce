# Florir Aromas — E-Commerce

A PHP-based e-commerce system for selling aromas and incense products, with a full administrative panel for managing products, clients, and orders.

---

## About

**Florir Aromas** is a web application developed for real usage in an academic context. The system covers both the customer-facing storefront and an administrative interface for managing the full business flow — from registering suppliers and products to tracking orders.

The focus of the project is on backend logic and the practical application of web development concepts using PHP and MySQL.

---

## Features

- **Products** — full CRUD (create, read, update, delete)
- **Clients** — customer registration and data management
- **Suppliers** — supplier records linked to products
- **Orders** — order registration and tracking
- **Authentication** — login system with session control
- **File uploads** — support for uploading images and documents
- **Admin panel** — dedicated interface for internal operations

---

## Tech Stack

| Layer    | Technology        |
|----------|-------------------|
| Backend  | PHP               |
| Database | MySQL             |
| Frontend | JavaScript, CSS   |

---

## Project Structure

```
florir-aromas/
│
├── auth/           # Authentication and session control
├── clientes/       # Client module
├── fornecedor/     # Supplier module
├── includes/       # Shared files (database connection, helpers, header)
├── pages/          # Main application pages
├── pedido/         # Order creation logic
├── pedidos/        # Order listing and management
├── produtos/       # Product module
├── scripts/        # JavaScript files
├── styles/         # CSS files
├── uploads/        # Server-uploaded files
└── index.php       # Application entry point
```

---

## Getting Started

### Prerequisites

- PHP 7.4+
- MySQL 5.7+
- [XAMPP](https://www.apachefriends.org/) (or any local server with PHP and MySQL support)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/florir-aromas.git
   ```

2. Copy the project folder into XAMPP's `htdocs` directory:
   ```
   C:/xampp/htdocs/florir-aromas/
   ```

3. Create the database and import the `.sql` file (if available):
   ```sql
   CREATE DATABASE florir_aromas;
   ```

4. Configure the database connection in `includes/conexao.php`:
   ```php
   $host = "localhost";
   $usuario = "root";
   $senha = "";
   $banco = "florir_aromas";
   ```

5. Open in your browser:
   ```
   http://localhost/florir-aromas/
   ```

---

## What I Practiced

- Backend development with plain PHP
- MySQL integration — queries, inserts, updates, and deletions
- Building CRUD systems across multiple related entities
- User authentication and session management
- Structuring a mid-sized web application into modules
- Integrating frontend (HTML/CSS/JS) with backend (PHP)
- File upload handling on the server

---

## Notes

This project was built for practical use in an academic context and reflects a real-world development process. The priority was **functionality** and **data management**, using a straightforward modular structure without any frameworks.
