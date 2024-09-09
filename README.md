# Laravel eCommerce Application

## Author
**Shubham Jethva**

Welcome to my Laravel eCommerce platform. This application provides a comprehensive and scalable online shopping experience, featuring product displays, a shopping cart, and a checkout system, all powered by Laravel.

---

## Features

### 1. Products
- **Product Display**: The application lists all available products with detailed information, including:
  - Product name
  - Price
  - Description
  - Category
  - Stock availability

### 2. Cart
- **Add to Cart**: Users can add products to their shopping cart.
- **Cart View**: A detailed view of all products in the cart, including:
  - Product names
  - Quantities
  - Prices
  - Subtotal and total cost

### 3. Checkout
- **Order Review**: Users can review their order before proceeding to payment.
- **Order Confirmation**: After successful payment, users receive an order confirmation with a summary of their purchase and an estimated delivery date.

### 4. User Authentication
- **User Registration**: New users can register for an account.
- **User Login**: Returning users can log in with their credentials to access their account.

---

## Installation

To run this project locally, follow the steps below:

1. **Clone the repository**:
   ***clone the repo from the github:
   git clone https://github.com/shubham-910/laravel-ecommerce.git

   ***Visit the cloned directory:
   cd laravel-ecommerce

   ***To install the dependencies:
   composer install

   ***To copy .env file:
   cp .env.example .env

   ***To connect with the database, you can add more configurations if you want. (Cache)
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_db_username
   DB_PASSWORD=your_db_password

   ***To generate key for the project:
   php artisan key:generate

   ***To migrate tables in the database:
   php artisan migrate

   ***To make port available for the project:
   php artisan serve

**Open any browser and write http://127.0.0.1:8000 and hit enter your site will be up and running**

