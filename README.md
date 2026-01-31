# 🛒 MERN E-Commerce Web Application

A full-stack **eCommerce web application** built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
The project includes a customer-facing storefront and an admin dashboard for managing product inventory.

This project was developed for learning purpose, focusing on real-world full-stack development concepts.

---

## 🚀 Features

### User Features

- Browse products by category
- View detailed product information
- Add and remove items from cart
- Persistent cart across login/logout
- User authentication using JWT

### Admin Features

- Add products (Phones, Tablets, Laptops, Audio)
- View and manage inventory
- Remove products from database
- Real-time updates reflected on frontend

---

## 🧠 Project Structure

ECOMMERCE_WEBAPP
│
├── frontend → Customer-facing React application
├── admin → Admin dashboard (React)
└── backend → Node.js & Express REST API

---

## 🛠️ Tech Stack

- Frontend: React, Vite, JavaScript, CSS
- Backend: Node.js, Express, JWT
- Database: MongoDB Atlas
- Tools: Git, npm, REST APIs

---

## ▶️ Running the Project Locally

1. Clone the repository

```bash
git clone https://github.com/Shyamatluri4/eCommerce_website.git
cd ECOMMERCE_WEBAPP
```

2. Backend Setup

```bash
cd backend
npm install
```

Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start backend:

```bash
npm start
```

3. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

4. Admin Dashboard Setup

```bash
cd ../admin
npm install
npm run dev
```
