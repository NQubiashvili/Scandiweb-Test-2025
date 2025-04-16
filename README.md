# Scandiweb-Test-2025
Scandiweb-Test-2025 eCommerce platform

- **Backend**: PHP, MySQL, GraphQL
- **Frontend**: React.js, Apollo Client, TailwindCSS
- **Utilities**: phpdotenv, react-toastify, dompurify, html-react-parser

## Overview

This application provides a simple eCommerce platform featuring product listings and cart functionality. It includes two main pages:

1. **Product Listing Pages (Categories)**

   - Displays a list of products within a selected category.
   - Serves as the default view of the website, showcasing the first category upon initial load.

2. **Product Details Page (PDP)**
   - Shows detailed information about a selected product, including images and descriptions.
   - Allows users to configure their product options before adding the item to the cart.
   - Features an "Add to Cart" button for seamless shopping.

## Getting Started

To get started, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/NQubiashvili/Scandiweb-Test-2025.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Scandiweb-Test-2025
   ```

3. **Install Dependencies:**

   ```bash
   composer install
   cd client && npm install
   ```

4. **Configure Environment:**

   - Rename the `.env.example` file in the root directory to `.env` and update the necessary variables.

   ```bash
    mv .env.example .env
   ```

5. **Database Setup:**

   - Create a database with the same name specified in `.env` (default is `scandiweb_ecommerce_task`).
   - Run the SQL script found in `schema.sql` file in the root directory to create the required tables with appropriate schema and relations.

6. **Serve or Build the Frontend:**

   ```bash
   cd client

   # For development:
   npm run dev

   # For production:
   npm run build
   ```

7. **Run the Start Script with No Timeout:**
   ```bash
   composer run-script start --timeout=0
   ```

## Prerequisites

Before you begin, ensure you have the following software installed on your system to run the project successfully:

- [PHP](https://www.php.net/) (Hypertext Preprocessor)
- [MySQL](https://www.mysql.com/) (or any other compatible relational database)
- [Composer](https://getcomposer.org/) (Dependency Manager for PHP)
- [NPM](https://nodejs.org/en/download) (Node Package Manager needed for Reactjs)
