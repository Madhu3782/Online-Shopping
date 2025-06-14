# 🛒 Online Shopping Website

This is a basic online shopping website built using HTML, CSS, JavaScript, and PHP with XAMPP server for backend and database operations.

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
└── LICENSE              # (if applicable)
