# 🍔 QuickBites - Full Stack Project

A robust food ordering platform connecting customers, restaurants, and administrators. Customers can browse menus, place orders, and make secure payments. Restaurants manage menus and orders, while admins monitor system-wide activities.

---

## 🚀 Features

### 🍽 Client (Frontend)
- 🧍‍♂ *User Registration & Login*
- 🍔 *Menu Browsing & Food Selection*
- 🛒 *Cart System & Order Placement*
- 💳 *Secure Payment Integration*
- 📜 *Order History & Tracking*
- 🌐 *Responsive UI* using Tailwind CSS

### 🏪 Restaurant Panel
- 🧾 *Menu Management* — Add, edit, remove food items
- 🧑‍🍳 *Order Management Dashboard*
- 📊 *Sales Analytics with Recharts*
- 🔔 *Real-time Notifications*
- 📥 *Export Orders to Excel (XLSX)*

### 🧑‍💼 Admin Panel
- 👥 *User & Restaurant Management*
- 📦 *System-wide Order Monitoring*
- 📊 *Admin Dashboard with Charts*
- 🔒 *Secure Login with JWT*

### 🧠 Backend API
- RESTful API with Express.js
- MongoDB + Mongoose for data handling
- Authentication & Authorization using JWT
- Email Support via SendGrid & Nodemailer
- Cloudinary for image storage
- Stripe integration for payments

---

## ⚙ Tech Stack

- *Frontend*: React.js, Vite, Tailwind CSS, React Router DOM, Axios
- *Backend*: Node.js, Express.js
- *Database*: MongoDB (via Mongoose)
- *Authentication*: JWT, Cookies
- *Payment*: Stripe
- *Others*: Cloudinary, Nodemailer, XLSX, Lucide React, Toastify, Recharts

---

## 💻 Installation

1. *Clone the repository*

bash
git clone https://github.com/yourusername/QuickBites


2. *Install dependencies*

bash
# Backend Setup
cd backend
npm install

# Client Frontend Setup
cd ../frontend
npm install

# Admin Panel Setup
cd ../admin-frontend
npm install

# Restaurant Panel Setup
cd ../restaurant-frontend
npm install


3. *Run development servers*

bash
# Start Backend
cd backend
npm run dev

# Start Client Frontend
cd ../frontend
npm run dev

# Start Admin Frontend
cd ../admin-frontend
npm run dev

# Start Restaurant Frontend
cd ../restaurant-frontend
npm run dev


---

## 📁 Project Structure


QuickBites/
├── backend/               # Node.js + Express.js API
├── frontend/              # Customer-facing React App
├── admin-frontend/        # Admin Dashboard Panel
├── restaurant-frontend/   # Restaurant Dashboard Panel


---

Enjoy your meal with QuickBites! 🍔🚀
