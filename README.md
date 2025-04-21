# 🍽️ QuickBites - Multi-Restaurant Food Delivery Platform

QuickBites is a full-featured, modern web application that enables users to browse multiple restaurants, explore diverse menus, place food orders, and track deliveries in real-time. The platform includes specialized dashboards for customers, restaurant partners, and administrators.

---

## 🚀 Features

- 🏪 **Multi-Restaurant Support** — Order from various restaurants in one app.
- 👤 **User Registration & Secure Login** — JWT-authenticated user system.
- 📖 **Restaurant & Menu Browsing** — Discover dishes and filter options easily.
- 🛒 **Smart Cart System** — Add, remove, and manage quantities smoothly.
- 💳 **Order & Payment Workflow** — Place orders and make secure payments.
- 📦 **Order History & Live Tracking** — Follow real-time delivery updates.
- 💬 **Feedback System** — Leave reviews only after delivery is complete.
- 🧑‍💻 **Role-based Dashboards**:
  - Customer App
  - Restaurant Partner Panel
  - Admin Panel for complete platform control.
- 💡 **Fully Responsive Design** — Optimized for all screen sizes.

---

## ⚙️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JSON Web Token (JWT)

---

## 💻 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Keval-Patel01/QuickBites-Food-Delivery-Website
```

2. **Install dependencies for each part**

```bash
cd Backend
npm install

cd ../Client_Frontend
npm install

cd ../Admin_Frontend
npm install

cd ../Restaurant_Frontend
npm install
```

3. **Run all development servers**

```bash
cd Backend
npm run dev

cd ../Client_Frontend
npm run dev

cd ../Admin_Frontend
npm run dev

cd ../Restaurant_Frontend
npm run dev
```

---

## 📂 Project Structure

```
├── Admin_Frontend/           # Admin Dashboard for platform management
├── Client_Frontend/          # Customer Application (Multiple Restaurant Browser)
├── Restaurant_Frontend/      # Restaurant Partner Panel (Order & Menu management)
├── Backend/                  # Node.js API Server (Authentication, Orders, Payments, Feedback)
```

Enjoy your meal with QuickBites! 🍔🚀
