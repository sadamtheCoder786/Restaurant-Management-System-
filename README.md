# 🍽️ Restaurant Management System

A full-featured Restaurant Management System built using **Node.js**, **Express.js**, **PostgreSQL**, and a responsive **Tailwind CSS** frontend.

---

## 🚀 Features

- 📋 Manage Orders: Add, view, update, and delete customer orders.
- 🧾 Menu Management: Add and edit menu items with ease.
- 👥 Staff Management: Track staff information and roles.
- 📅 Reservations: View and manage table reservations with time slots.
- 💵 Payments: Record payment details, methods, and order links.
- 📊 Admin Dashboard: Centralized view with organized navigation.
- 🌐 Responsive Design: Works on desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack

| Layer     | Tech Used                        |
|-----------|----------------------------------|
| Frontend  | HTML, Tailwind CSS, FontAwesome |
| Backend   | Node.js, Express.js              |
| Database  | PostgreSQL                       |

---

## 📁 Folder Structure

```
restaurant-app/
│
├── node_modules/               # Installed dependencies
├── public/                     # Frontend files
│   ├── css/                    # (optional) Custom CSS
│   ├── webpages/
│   │   ├── customers/
│   │   │   └── customers.html
│   │   ├── dining tables/
│   │   │   └── tables.html
│   │   ├── menu/
│   │   │   └── menu.html
│   │   ├── orders/
│   │   │   └── orders.html
│   │   ├── payments/
│   │   │   └── payments.html
│   │   └── staff/
│   │       ├── staff.html
│   │       ├── login.html
│   │       ├── register.html
│   │       └── index.html
│
├── routes/                     # Express route handlers
│   ├── auth.js
│   ├── customers.js
│   ├── menu.js
│   ├── orders.js
│   ├── payments.js
│   ├── reservations.js
│   └── staff.js
│
├── .env                        # Environment variables (DB config, etc.)
├── db.js                       # PostgreSQL connection pool
├── server.js                   # Main Express server
├── package.json                # Project metadata & dependencies
├── package-lock.json           # Exact dependency tree
└── README.md                   # Project documentation
```

---

## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/restaurant-app.git
   cd restaurant-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up PostgreSQL Database**
   - Create a PostgreSQL database.
   - Import the provided SQL schema (if available).
   - Update `.env` or `db.js` with your DB credentials.

4. **Run the server**
   ```bash
   node server.js
   ```

5. Open in your browser:
   ```
   http://localhost:3000
   ```

