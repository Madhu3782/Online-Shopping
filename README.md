# 🛒 Online Shopping Website

Overview
This is a complete e-commerce web application built with PHP, MySQL, HTML, CSS, and JavaScript that allows users to browse products, add items to a shopping cart, and complete purchases with payment processing.
This is a mini project for building an **Online Shopping Website** using web development technologies. The site allows users to register, log in, browse products, add them to a shopping cart, and proceed to checkout. The admin can also manage product listings.

This project is ideal for learning how to:
- Connect frontend with PHP backend
- Use forms for login/registration
- Work with a MySQL database through phpMyAdmin
- Handle sessions and basic CRUD operations
## 🚀 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL (via XAMPP)

## 📂 Features

- User registration and login
- Product catalog display
- Add to cart functionality
- View cart and checkout
- Admin product management (optional)

## ⚙️ Installation & Setup

1. Install **XAMPP**: [Download here](https://www.apachefriends.org/)
2. Clone or download this project into `htdocs` directory of XAMPP.
3. Start **Apache** and **MySQL** from XAMPP Control Panel.
4. Import the `shopping.sql` file (if any) into **phpMyAdmin**.
5. Open browser and go to `http://localhost/your-project-folder-name`

FILE STRUCTURE
project-root/

├── 
│   ├── css/
│   │   ├── login1.css
│   │   └── registeration.css
│   ├── js/
│   │   ├── login.js
│   │   └── registeration.js
│   └── images/          # (for product images if any)
│
├── includes/            # (for reusable components if any)
│
├── public/              # (main web-accessible files)
│   ├── cart.php
│   ├── checkout.php
│   ├── login.html
│   ├── login.php
│   ├── logout.php
│   ├── payment.php
│   ├── registeration.html
│   ├── registeration.php
│   ├── shopping.php
│   └── view_cart.php
│
├── database/            # (SQL files for database setup)
│   └── shopping_db.sql  # (your database schema)
│
├── README.md            # (project documentation)
└── 
