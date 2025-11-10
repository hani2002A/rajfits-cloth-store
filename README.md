# 👕 RajFits Cloth Store

RajFits Cloth Store is a full-featured **e-commerce web application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project includes a customer-facing online store as well as an admin dashboard for managing products, orders, and subscribers.

> It offers real-time order tracking, email-based coupon systems, secure login, and a seamless shopping experience across categories like Men, Women, and Kids.

---

## 🌟 Features

### 🛍️ User Side

- Browse & filter clothes by category, subcategory, and size
- Add to cart with selected sizes
- Account-based authentication (JWT)
- Create account, login, and personalized cart/orders
- Forgot password support via Contact page
- Checkout with:
  - Address form
  - Payment method selection (Card, UPI, Cash on Delivery)
- Order confirmation with live tracking status
- Email subscription with coupon code & redeem link (via Nodemailer)
- Mobile responsive design

---

### 📄 Pages

1. **Home** – Store intro and promotions  
2. **Collections** – Filter and search products  
3. **Contact** – Store location and support  
4. **About** – Brand story   
5. **Cart Page** – View & update cart, add quantities  
6. **Account Page** – Profile, login/logout, and orders  
7. **Orders (inside Account)** –  
   - Product summary  
   - Quantity & total  
   - Payment method  
   - Live order status updates  
8. **Login/Register (inside Account)**  
9. **Checkout Page** –  
   - Fill address  
   - Choose payment  
   - Place order  
10. **Footer** – Contact info, brand logo, quick links

---

## 🔐 Authentication

- JWT-based login system
- Passwords are hashed using bcrypt
- Auth-protected routes for cart, orders, and admin
- Each user's cart & orders are stored securely under their account

---

## ✉️ Email Subscription (Nodemailer)

- Subscribe to the store’s newsletter
- Receives a welcome email with:
  - Coupon Code
  - "Redeem Now" button that links to the store

---


## 🧮 Admin Panel

A secure admin dashboard with the following features:

### 🔐 Admin Authentication
- JWT-based login system
- Role-based access (admin only)
- Protected admin routes

### 📦 Product Management (CRUD)
- Create, Read, Update, Delete products
- Pagination & search filters
- Upload product images (via Cloudinary)
- Category, price, and stock management
- Optional: Bulk import via JSON/CSV

### 📬 Order Management
- View all orders with filters (status/date range/search)
- Update order status: Pending → Processing → Shipped → Delivered → Cancelled
- View order details (items, address, total)
- Export selected orders to CSV
- Add optional admin notes

### 📊 Admin Dashboard
- KPIs: Total Orders, Pending Orders, Revenue, Total Products
- Quick actions: Add Product, View Orders
- Responsive admin layout with confirmation modals

## 🧰 Tech Stack

**Frontend:**
- React.js
- React Router (for page routing)
- Styled CSS 

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB
- Mongoose

**Authentication:**
- JSON Web Tokens (JWT) for session management
- bcrypt for password hashing and security

**Email Service:**
- Nodemailer (used to send coupon/subscription emails)

**Image/File Upload :**
- Cloudinary

## 🚀 Setup Instructions

### 1. Clone the repository

git clone https://github.com/yourusername/rajfits-cloth-store.git
cd rajfits-cloth-store

### 2. Install dependencies

#For backend:

cd backend
npm install

#For frontend:

cd frontend
npm install

### 4. Run the project

# Run backend
npm run server

# Run frontend
npm start

### 5. Access the app

User Site: http://localhost:3000
Admin Panel: http://localhost:3000/admin/rajfits25

---

### ✅ **1.2 Admin Credentials** — *Add right after the Admin Panel section*
The assignment requires you to provide test admin login info.

## 👨‍💼 Admin Credentials

Email: admin@example.com  
Password: Admin@12345  

**Admin Panel URL:** `/admin/rajfits25`


## ⚠️ Important Note

This application is currently **optimized for desktop use**. While it may load on mobile devices, certain features and layouts are not fully responsive or tested for smaller screen sizes.

## 🏁 Conclusion

RajFits Cloth Store demonstrates a complete end-to-end MERN e-commerce solution with modern authentication, responsive design, admin management, and secure backend APIs — aligned with Sepnoty Technologies’ Full Stack Developer assignment requirements.
