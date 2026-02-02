# 🛒 MERN E-Commerce Web Application

A full-stack **eCommerce web application** built using the **MERN stack (MongoDB, Express, React, Node.js)**.
The project includes a customer-facing storefront and an admin dashboard for managing product inventory.

This project was developed for learning purposes, focusing on real-world full-stack development concepts.

---

## 🚀 Features

### User Features

- Browse products by category (phones, laptops, audio, etc.)
- View detailed product information
- Add and remove items from cart
- Persistent cart across login/logout
- User authentication using JWT
- Responsive design

### Admin Features

- Add products (Phones, Tablets, Laptops, Audio)
- View and manage inventory
- Remove products from database
- Real-time updates reflected on frontend
- Product image upload

---

## 🧠 Project Structure

```
ECOMMERCE_WEBAPP/
│
├── frontend/ → Customer-facing React application (using Create React App)
├── admin/ → Admin dashboard (React with Vite)
├── backend/ → Node.js & Express REST API
├── README.md
└── .gitignore
```

---

## 🛠️ Tech Stack

- **Frontend**: React, JavaScript, CSS
- **Admin**: React, Vite, JavaScript, CSS
- **Backend**: Node.js, Express.js, JWT, Multer (for file uploads)
- **Database**: MongoDB
- **Tools**: Git, npm, REST APIs

---

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (local installation or MongoDB Atlas)
- npm or yarn

---

## ▶️ Running the Project Locally

1. **Clone the repository**

```bash
git clone https://github.com/Shyamatluri4/eCommerce_website.git
cd ECOMMERCE_WEBAPP
```

2. **Backend Setup**

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/ecommerce
JWT_SECRET=your_secret_key_here
```

Start the backend server:

```bash
node index.js
```

The backend will run on `http://localhost:5000`

3. **Frontend Setup**

```bash
cd ../frontend
npm install
npm start
```

The frontend will run on `http://localhost:3000`

4. **Admin Dashboard Setup** (Optional)

```bash
cd ../admin
npm install
npm run dev
```

The admin dashboard will run on `http://localhost:5173` (default Vite port)

---

## 🔧 API Endpoints

### Authentication

- `POST /login` - User login
- `POST /signup` - User registration

### Products

- `GET /all-products` - Get all products
- `GET /new-collection` - Get new collection products
- `GET /popular-phones` - Get popular phones
- `GET /related-{category}` - Get related products by category

### Cart Management

- `POST /addtocart` - Add item to cart (requires auth)
- `POST /removefromcart` - Remove item from cart (requires auth)
- `POST /getcart` - Get user's cart (requires auth)

### Admin

- `POST /upload` - Upload product image
- `POST /addproduct` - Add new product
- `POST /removeproduct` - Remove product

---

## 📸 Screenshots

### Homepage
![Homepage](https://github.com/user-attachments/assets/01bc042e-b5aa-48f7-9b76-e2178e838852)

### Footer
![Footer](https://github.com/user-attachments/assets/b6fc3124-74fd-4a16-a4aa-e59a9aad74e4)

### Loginpage
![Loginpage](https://github.com/user-attachments/assets/733a5690-a026-47fb-931e-a90b4b222730)

### ShoppingCart
![ShoppingCart](https://github.com/user-attachments/assets/4142fc66-9101-43da-8127-2af2123cedc8)
