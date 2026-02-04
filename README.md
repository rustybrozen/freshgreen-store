# E-commerce Platform


## Features

### Customer-Facing Features
- **User Authentication**: Customers can register, log in, and manage their accounts.
- **Product Catalog**: Browse products by category, search for specific items, and view detailed product pages.
- **Shopping Cart**: Add products to a shopping cart, update quantities, and remove items.
- **Checkout Process**: A seamless checkout process for placing orders.
- **Order Tracking**: Customers can view their order history and track the status of their orders.
- **User Profile**: Manage personal information, shipping addresses, and view order history.

### Admin Panel Features
- **Dashboard**: An overview of key metrics such as sales, orders, and new customers.
- **Product Management**: Add, edit, and delete products. Manage product images, stock levels, and pricing.
- **Category Management**: Organize products into categories for easy navigation.
- **Order Management**: View and manage customer orders, update order statuses, and handle payments.
- **User Management**: View and manage customer accounts.
- **Admin Profile**: Manage admin user profiles.


## Setup and Installation

To get the project up and running on your local machine, follow these steps:

1. **Clone the repository**:

2. **Install dependencies**:
   ```bash
   composer install
   npm install
   ```

3. **Set up environment variables**:
   - Copy the `.env.example` file to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Generate an application key:
     ```bash
     php artisan key:generate
     ```

4. **Configure the database**:
   - Create a database for the application.
   - Update the database credentials in your `.env` file.

5. **Run database migrations**:
   ```bash
   php artisan migrate
   ```

6. **Seed the database** (optional):
   - If you want to populate the database with sample data, run the database seeders:
     ```bash
     php artisan db:seed
     ```

7. **Build frontend assets**:
   ```bash
   npm run build
   ```

8. **Run the development server**:
   ```bash
   php artisan serve
   ```


## Usage

- **Admin Panel**: Access the admin panel by navigating to `/admin`.
- **Customer Storefront**: The main storefront is accessible at the root URL (`/`).




## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
