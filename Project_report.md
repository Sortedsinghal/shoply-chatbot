# 🛒 Shoply – Final Project Report

## 📘 Project Overview

**Shoply** is an AI-powered full-stack chatbot built for e-commerce product search and exploration. Developed as part of the Uplyft Full Stack Intern Case Study, this project showcases seamless integration between a smart chat interface and a structured backend product database.

The chatbot enables users to interact using natural language, receive instant product recommendations, and explore categorized listings across books, electronics, apparel, and more.

---

## 🧱 Technology Stack

### 🔹 Frontend
- **ReactJS** – SPA architecture and chat interface rendering
- **JavaScript (ES6+)** – UI interactivity and logic
- **HTML5 & CSS3** – Responsive layout and styling
- **Emoji-based Favicon** – Minimalist visual branding

### 🔸 Backend
- **Python + Flask** – REST API to handle user queries
- **Flask-CORS** – Enables frontend-backend communication
- **SQLite** – Lightweight relational database with 100+ mock and real product entries

---

## 📊 Sample Queries & Responses

| User Query         | Bot Response Sample                                      |
|--------------------|----------------------------------------------------------|
| `books`            | Atomic Habits, Zero to One, Rich Dad Poor Dad, etc.     |
| `product 1`        | Product 1 (only)                                          |
| `zero to one`      | Zero to One (exact match logic)                          |
| `electronics`      | iPhone 14 Pro, Dell XPS 15, AirPods Pro                  |
| `show all`         | Displays all 100+ products                               |

---

## 🔍 Feature Highlights

- 💬 Natural language product queries
- ✅ Exact and partial match logic via SQL
- 📚 Smart category filtering (books, electronics, etc.)
- 📜 Timestamped chat history with export option
- 📱 Fully responsive UI (desktop, tablet, mobile)
- 🧠 Popular category shortcut buttons (Books, Electronics)
- 🧾 Database seeded with real + dummy products

---

## 🧪 Implementation Process

1. **Database Initialization**
   - SQLite used for simple RDBMS storage
   - Script auto-populates 100+ product entries at runtime

2. **Backend API Design**
   - Flask endpoint `/api/chat` processes all user inputs
   - Logic first checks for exact matches, then fuzzy fallback

3. **Frontend Development**
   - Built with ReactJS and hooks
   - Styled for usability and responsiveness
   - Chat state persisted and rendered cleanly
   - Timestamping and “Export Chat” features implemented

---

## 📈 Key Learnings & Challenges

| Area             | Insight                                                                 |
|------------------|-------------------------------------------------------------------------|
| Backend Logic    | Learned to balance exact and partial matches in SQL                     |
| React Components | Managed chat state, scroll behavior, and component separation           |
| UX Design        | Optimized flow with buttons, timestamps, and minimal clicks             |
| Debugging        | Solved frontend-backend CORS issues and substring filtering bugs        |
| Efficiency       | Used SQLite’s simplicity for fast bootstrapping of the DB               |

