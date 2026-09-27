# MERN Ecommerce Application

This is a full-stack E-commerce web application built using the MERN stack (MongoDB, Express.js, React, Node.js), powered by Vite and styled with Tailwind CSS.

---

## 📁 Project Structure


MERN Ecommerce/
├── backend/            # Express Server, Routes, Controllers & Database Models
│   ├── config/         # Database Connection Configurations
│   ├── controllers/    # Logic for Auth, Products, Cart, Orders, & Addresses
│   ├── models/         # Mongoose Schemas (User, Product, Cart, Order, Address)
│   └── routes/         # Express API Routes
└── frontend/           # React (Vite) User Interface
├── src/
│   ├── admin/      # Admin Dashboard Components
│   ├── api/        # Axios API Integrations & Requests
│   ├── components/ # Reusable UI Components
│   └── pages/      # Application Pages / Views
└── public/         # Static Assets & Icons



---

## ✨ Features

- **User Authentication & Authorization**: Secure User Sign-up, Login, and Protected Routes using JWT (JSON Web Tokens) and Bcryptjs.
- **Product Management**: Browse, search, filter, and view detailed product information.
- **Shopping Cart System**: Add to cart, remove items, update quantities, and calculate totals in real-time.
- **Address Management**: Save, update, and manage multiple delivery addresses.
- **Order Management**: Checkout functionality and order status tracking.
- **Admin Dashboard**: Dedicated interface for admins to manage products, categories, and customer orders.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework/Library:** React.js (via Vite)
- **Styling:** Tailwind CSS
- **Routing:** React Router
- **HTTP Client:** Axios
- **Icons:** SVG Custom Icons

### **Backend**
- **Runtime Environment:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB (via Mongoose ORM)
- **Security & Auth:** JSON Web Token (JWT), Bcryptjs, CORS
- **Environment Management:** Dotenv

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB Database (Local instance or MongoDB Atlas URI)

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd "MERN Ecommerce"


Backend
npm start

Fontend
npm run dev