# TechShop - E-Commerce Website

TechShop is a front-end e-commerce website built using **HTML, CSS, and JavaScript**. The project was developed to demonstrate core web development concepts, including responsive design, dynamic product pages, and client-side shopping cart functionality using Local Storage.

## Features

- 🛍️ Browse a catalogue of electronic products
- 📄 Individual product detail pages
- 🛒 Shopping cart powered by Local Storage
- ➕ Add products to cart with adjustable quantities
- 💾 Cart data persists after refreshing the page
- 📱 Responsive layout for desktop and mobile devices
- 🎨 Modern UI inspired by contemporary e-commerce websites

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Local Storage API

## Project Structure

```
TechShop/
│
├── index.html              # Homepage
├── products.html           # Product catalogue
├── product-details.html    # Individual product page
├── cart.html               # Shopping cart
│
├── css/
│   └── style.css
│
├── js/
│   ├── products.js
│   ├── product.js
│   ├── cart.js
│   └── main.js
│
├── img/
│   └── ...
│
└── README.md
```

## Shopping Cart

The shopping cart uses the browser's **Local Storage API** to save products between page refreshes.

Each cart item is stored as a JSON object containing:

```javascript
{
    image: "img/electr/earbuds.jpg",
    name: "EarFun Air Pro 3 Earbuds",
    price: 49.99,
    quantity: 1
}
```

These objects are stored inside a JSON array under the `cart` key in Local Storage.

## Learning Objectives

This project demonstrates:

- DOM Manipulation
- Event Handling
- Responsive Web Design
- Local Storage
- JSON Objects
- Dynamic Content Loading
- Product Catalogue Design

## Future Improvements

- Product search and filtering
- User accounts and authentication
- Checkout process
- Payment gateway integration
- Wishlist functionality
- Product reviews and ratings
- Backend database integration
- Admin dashboard for product management

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/techshop.git
```

Navigate into the project:

```bash
cd techshop
```

Open `index.html` in your browser, or use the VS Code Live Server extension.

## Screenshots

Add screenshots of:

- Homepage
- Product Catalogue
- Product Detail Page
- Shopping Cart

## Author

Developed as part of a Web Development project using HTML, CSS, and JavaScript.
