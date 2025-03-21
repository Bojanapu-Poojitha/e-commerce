# E-Commerce Application 🛒

## Overview
This is a full-stack E-Commerce web application where users can browse products, add them to the cart, and place orders.

## Features
- 🏠 Homepage with product listings
- 🔍 Search bar to find products
- 🛍️ Add to cart and Wishlist
- 💳 Checkout feature
- 📦 My Orders and User Profile pages

## Tech Stack
- Frontend: ReactJS ⚛️
- Backend: Node.js & Express.js 🚀
- Database: MySQL 🗄️

## Installation & Setup
```sh
npm install  # Install dependencies
npm start    # Start the development server

## 📌 Description  
This PR introduces the "Add to Cart" functionality in the e-commerce application. Users can now add products to their cart and view selected items before checkout.

## 🔹 Changes Made  
- Created `Cart.js` React component.  
- Added Redux state management for cart items.  
- Integrated `/api/cart` API with backend (Node.js & Express).  
- Updated UI with a shopping cart icon.

## 🔍 How to Test  
1. Run the frontend and backend using `npm start`.  
2. Go to the homepage and select a product.  
3. Click **"Add to Cart"** and verify that the item appears in the cart.  

## ✅ Checklist  
- [x] Code follows the project guidelines.  
- [x] Unit tests have been added.  
- [x] API calls are working correctly.  

## 🔗 Related Issues  
Closes #15

