# eCommerce Website

## Overview
This project is a fully functional **eCommerce Website** built using **PHP & MySQL**. It allows users to browse products, add them to their cart, and place orders. The system includes user authentication, a shopping cart system, and order management.

## Features
- **User Authentication**: Users can sign up, log in, and manage their accounts.
- **Product Management**: Display products with details including name, price, image, and category.
- **Shopping Cart**: Users can add, update, or remove products from their cart.
- **Checkout Process**:
  - Users enter their shipping details (name, number, email, address, state, country, pin code)
  - Place an order which gets stored in the database.
- **Order Management**: The admin can manage orders and track sales.

## Technologies Used
- **Frontend**:
  - HTML, CSS, JavaScript
  - Font Awesome for icons
  
- **Backend**:
  - PHP (Procedural & PDO for secure database queries)
  - MySQL for data storage
  
- **Other Tools**:
  - CapCut for video content creation (if needed for marketing)
  - Hosting & domain setup for deployment

## Installation & Setup
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/softboyai/ecommerce-platform.git
   cd ecommerce-platform
   ```

2. **Setup Database**:
   - Import `database.sql` file (if available) into MySQL.
   - Create a database and configure it in `components/connect.php`:
   ```php
   $conn = new PDO("mysql:host=localhost;dbname=ecomm_db", "root", "");
   ```

3. **Run the Project**:
   - Place the project files inside your local server directory (`htdocs` for XAMPP or `www` for WAMP).
   - Start Apache and MySQL from XAMPP or WAMP.
   - Open `http://localhost/ecommerce-platform/` in your browser.

## File Structure
```
/ecommerce-website
│── components/
│   ├── connect.php  # Database connection
│   ├── user_header.php  # Header for logged-in users
│   ├── footer.php  # Common footer
│── css/
│   ├── style.css  # Styling file
│── js/
│   ├── script.js  # JavaScript functions
│── checkout.php  # Handles checkout process
│── index.php  # Homepage
│── user_login.php  # User login page
│── user_register.php  # User registration
│── cart.php  # Shopping cart page
│── orders.php  # Order management
│── admin/  # Admin panel files
│── images/  # Product images
│── database.sql  # Database structure file
```

## Usage
1. **User Journey**:
   - Users register/login.
   - Browse products and add to cart.
   - Proceed to checkout, enter details, and place order.
   - Admin can manage orders.

2. **Admin Panel**:
   - Manage products, users, and orders.
   - View sales reports.

## Contribution
Contributions are welcome! Feel free to fork the repository and create pull requests.

## Contact
For any issues or suggestions, contact **Kamanzi Jean Marie Vianney** at **kamanzijeanmarievianney15@gmail.com**.

## License
This project is licensed under [MIT License](LICENSE).

