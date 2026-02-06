project:
  title: "QR Code Based Digital Menu & Ordering System"
  stack: "MERN Stack"
  description: >
    A full-stack digital menu and ordering system where customers scan a QR code,
    place orders from their mobile phones, and the admin receives orders in real time.
    This project is beginner-friendly and built using the MERN stack.

features:
  customer_side:
    - Scan QR code to open the menu
    - Enter table number
    - Select food items using checkboxes
    - Automatic total bill calculation
    - Place order with confirmation alert

  admin_side:
    - View all customer orders
    - View table number, ordered items, total bill, and order time
    - Latest orders shown first
    - Auto-refresh orders
    - Notification when a new order is received

tech_stack:
  frontend: "React.js"
  backend: "Node.js, Express.js"
  database: "MongoDB Atlas"
  tools:
    - Git
    - GitHub
    - QR Code

project_structure:
  - qr-menu-mern/
  - backend/
  - frontend/
  - README.md

run_locally:
  backend:
    steps:
      - cd backend
      - npm install
      - npm start

  frontend:
    steps:
      - cd frontend
      - npm install
      - npm start

workflow:
  - Admin generates a QR code
  - Customer scans the QR code and opens the menu
  - Customer selects items and enters table number
  - Order is stored in MongoDB
  - Admin receives the order with notification

future_improvements:
  - Sound notification for admin
  - Online payment integration
  - Admin authentication system
  - Improved UI/UX
  - Real-time updates using Socket.IO

author:
  name: "Vidhi Borse"
  education: "2nd-year B.Tech Data Science student"
  interests:
    - Real-world MERN stack projects
    - Full-stack development

note: "If you like this project, please give it a star on GitHub ⭐"
