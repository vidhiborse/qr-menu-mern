# 🍽️ QR Code Based Digital Menu & Ordering System (MERN Stack)

A full-stack **Digital Menu and Ordering System** where customers scan a QR code, place orders from their mobile phones, and the admin receives orders in real time.

This project is built using the **MERN Stack** and is beginner-friendly.

---

## 🚀 Features

### 👨‍🍳 Customer Side
- Scan QR code to open the menu
- Enter table number
- Select food items using checkboxes
- Auto-calculated total bill
- Place order with confirmation alert

### 🧑‍💼 Admin Side
- View all customer orders
- See **table number, ordered items, total bill, and order time**
- Latest orders shown first
- Auto-refresh orders
- 🔔 Notification when a new order is received

---

## 🛠️ Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB Atlas  
- **Other Tools**: Git, GitHub, QR Code  

---

## ⚙️ How to Run Locally

### 1️⃣ Backend
```bash
cd backend
npm install
npm start

###2️⃣ Frontend
cd frontend
npm install
npm start
📱 How It Works
Admin generates a QR code

Customer scans the QR code → menu opens

Customer selects items and enters table number

Order is saved in MongoDB

Admin receives the order with a notification

🎯 Future Improvements
Sound notification for admin

Online payment integration

Admin login system

Improved UI/UX design

Real-time updates using Socket.IO

🙋‍♀️ Author
Vidhi Borse
2nd-year B.Tech Data Science student
Interested in building real-world MERN stack projects

⭐ If you like this project, please give it a star!
