# Yipp - Your eCommerce Retail Store

Your eCommerce retail store project is a web application that allows users to browse and purchase products online. It provides features such as browsing products, adding items to the cart, a shopping cart, authentication, checkout process, order viewing, search functionality, and responsiveness.

## Features

- **Browse Products:** Users can browse a list of available products.
- **Add Items to Cart:** Users can add items to their shopping cart.
- **Product Listing:** Display products with pagination.
- **Product Details:** View detailed information about a product.
  - Additional details
  - Customer reviews
  - Related products
- **Shopping Cart:**
  - Add and remove items from the cart
  - View the total cart amount
  - Proceed to checkout
- **Authentication:**
  - Login and Register functionalities
- **Checkout Process:**
  - Provide shipping address
  - Checkout using PayPal
  - Payment processing
- **View Orders:** Users can view their order history.
- **Search:** Search for products using keywords.
- **Responsiveness:** The application is responsive and works well on different devices.

## Getting Started

1. Clone this repository to your local machine.
2. Import the `yipp.sql` file into your MySQL database.
3. Edit the `credentials.php` file:
   - Update `WEBSITE_URL` with your website URL.
   - Update `MYSQL_HOSTNAME`, `MYSQL_USERNAME`, `DATABASE_NAME`, and `DATABASE_PASSWORD` with your MySQL database credentials.
   - Update `EMAIL_ADDRESS` and `EMAIL_PASSWORD` with your email credentials.

## Prerequisites

- Web server (e.g., Apache, Nginx)
- PHP 7.0 or higher
- MySQL database
- PayPal developer account for testing checkout

## Usage

1. Run the application on your web server.
2. Browse the products, add items to the cart, and proceed to checkout.
3. Use the authentication features to log in or register.
4. View your order history and search for products.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements, bug fixes, or new features.

## License

This project is licensed under the [MIT License](LICENSE).
