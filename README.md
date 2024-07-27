# **SELL-WELL Marketplace**

Welcome to **SELL-WELL**, your one-stop online marketplace for buying and selling products. Below is a guide to the different sections and functionalities of the website.

## **Project Structure**

The project consists of three main HTML pages:

- **`index.html`**: The login page and category selection.
- **`sell.html`**: The product listing and selling page.
- **`buy.html`**: The page to view and filter products for purchase.

## **File Overview**

### **`index.html`**

This is the login page where users can enter their credentials to access the marketplace. It contains:

- **Login Form**: Allows users to log in with a predefined username and password.
- **Category Selection**: Hidden until the user logs in, this section allows the user to choose between buying and selling.
- **JavaScript**: Handles form validation, login, and category redirection.

### **`sell.html`**

This page allows users to list products for sale. It includes:

- **Sell Form**: Users can input product details such as name, phone number, description, price, category, and image.
- **Product Categories**: Displays listed products organized by category.
- **Logout Button**: Allows users to log out and return to the login page.
- **JavaScript**: Manages form submission, product listing, and logout functionality.

### **`buy.html`**

This is the product browsing and purchasing page. It features:

- **Category Filter**: Users can filter products by category.
- **Product Listings**: Displays various products with an option to add them to the cart.
- **Cart**: Shows items added to the cart and total price.
- **Address Form**: Appears when the user proceeds to buy, to enter delivery details.
- **JavaScript**: Handles cart management, product filtering, and purchase processing.

## **How to Run**

1. **Open `index.html`**: Start by opening `index.html` in a web browser.
2. **Log In**: Use the username `Ragul` and password `ragulr7` to access the marketplace.
3. **Select Category**: Choose whether to buy or sell from the category selection.
4. **Navigate**: Depending on your choice, you'll be redirected to the respective page (`sell.html` or `buy.html`).

## **Dependencies**

No external libraries are used; plain HTML, CSS, and JavaScript are utilized.

## **Styling**

- **CSS Files**: Ensure to link your CSS files correctly in each HTML file to apply styling.
  - `style.css` for the login and category selection page.
  - `stylee.css` for the selling page.
  - `styles.css` for the buying page.

## **Features**

- **Login Validation**: Checks for specific username and password.
- **Product Listing**: Users can list products with details and images.
- **Product Filtering**: Users can filter products by category.
- **Cart Management**: Users can add products to the cart and see the total price.
- **Purchase Flow**: Users can provide delivery details and complete their purchase.

## **Troubleshooting**

- **Page Not Displaying Correctly**: Ensure all CSS files are linked properly and paths are correct.
- **JavaScript Errors**: Check the browser console for any JavaScript errors and debug accordingly.

