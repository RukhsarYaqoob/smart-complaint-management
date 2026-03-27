# 🚀 Smart Complaint Management System

A modern web-based Complaint Management System that allows users to submit, track, and manage complaints efficiently. This platform provides an admin dashboard to monitor all complaints and streamline issue resolution.

---

## 📌 Features

### 👤 User Panel
- User registration & login with JWT authentication
- Submit complaints with title, description, category, and priority
- Categories: Service, Technical, Staff, Delivery, Billing, Other
- Priority levels: Low, Medium, High
- View complaint status (Pending, In-Progress, Resolved, Closed)
- Track complaint history with timestamps
- View admin responses

---

### 🛠️ Admin Panel
- Secure admin login with protected routes
- Dashboard with complaint statistics (total, pending, resolved, etc.)
- View and manage all user complaints
- Filter by status, category, and priority
- Assign complaints to departments or staff
- Update complaint status with real-time changes
- Respond to user complaints directly

---

### 📊 Analytics
- Category-wise complaint statistics
- Monthly complaint trends
- Most frequent issues tracking
- Priority-based insights and breakdown

---

### 🔐 Security & System
- JWT-based authentication
- Password hashing with bcrypt
- Protected routes (user & admin)
- Input validation & error handling
- RESTful API architecture

---

### 🎨 Frontend Highlights
- Built with React.js
- Responsive UI (mobile-friendly)
- Clean and reusable components
- State management using Context API

---

### ⚙️ Backend Highlights
- Node.js & Express.js
- MongoDB with Mongoose
- Structured MVC architecture