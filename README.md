# E-commerce Platform


## Features

### Customer-Facing Features
- **User Authentication**
- **Product Catalog**
- **Shopping Cart**
- **Checkout Process**
- **Order Tracking**
- **User Profile**

### Admin Panel Features
- **Dashboard**
- **Product Management**
- **Category Management**
- **Order Management**
- **User Management**
- **Admin Profile**


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
