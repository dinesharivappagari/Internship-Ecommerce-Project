# 🛒 Full-Stack Ecommerce Web Application

A complete **MERN (MongoDB, Express, React, Node.js)** based Ecommerce platform with secure authentication, product management, cart functionality, payment integration, and an admin dashboard.

## ⚙️ Tech Stack

### Frontend
- React.js (with React Router)
- Bootstrap / Custom CSS
- Axios (for API calls)

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- Braintree (Payment Gateway)
- JWT (Authentication)
- dotenv (Environment configs)

---

## ✨ Features

### ✅ User Features
- Register & Login (JWT-based)
- Browse & Search Products
- Filter by Price & Category
- Add to Cart and Checkout
- Secure Payment with Braintree

### ✅ Admin Features
- Admin Dashboard
- Create/Update/Delete Products
- Manage Categories
- View Orders

---

## 📁 Folder Structure Overview

Ecommerce-App/
├── client/ # React frontend app
│ └── (React components, pages, etc.)
├── controllers/ # Route logic (auth, product, category)
├── helpers/ # Utility functions
├── middlewares/ # JWT + admin check
├── models/ # Mongoose schemas
├── routes/ # API route definitions
├── config/ # DB config (MongoDB connection)
├── .env # Environment variables
├── server.js # Express app entry point
└── README.md 

