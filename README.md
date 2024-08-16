# React Shopping Cart with Context API
![Screenshot 2024-08-16 220325](https://github.com/user-attachments/assets/c54abf2a-d0da-4d70-8bc6-284eb3c68341)


This project is a simple shopping cart application built using React and the Context API. It includes functionalities to add products to the cart, update the quantity of each item, remove items, and display the total quantity and amount.

## Features

- Add products to the cart.
- Increase or decrease the quantity of items in the cart.
- Remove items from the cart.
- Real-time updates to total quantity and amount.
- Responsive design with a clean interface.
- Smooth animations and modern UI styling.

## Project Structure

- `CartContext.js`: Manages the global state of the cart using the Context API and React's `useReducer`.
- `ProductList.js`: Displays the list of products available for purchase.
- `Cart.js`: Displays the cart items, with options to update quantity or remove items.
- `App.js`: The main component integrating the product list and cart.
- `styles.css`: Contains the styles for the entire application, including animations and responsive design.

## Getting Started

### Prerequisites

Ensure that you have Node.js and npm installed.

You can check if Node.js and npm are installed by running:
```bash
node -v
npm -v
