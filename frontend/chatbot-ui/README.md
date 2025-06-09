# 🛒 Shoply –  E-Commerce Chatbot

**Shoply** is a full-stack AI chatbot that helps users search and explore e-commerce products in natural language. Built using **ReactJS**, **Flask**, and **SQLite**, it offers seamless chat-based browsing with category filtering, smart matching, and conversation tracking.

---

## 🚀 Features

- 🔍 Search products by name or category (e.g., "books", "Product 1", "Zero to One")
- 📚 100 product entries with real + mock data
- 💬 Chat UI with auto-scrolling, timestamp, and chat history
- 🧠 Smart matching with exact and fuzzy logic
- 🔒 Modular Flask API with SQLite backend
- 📱 Responsive React frontend (mobile/tablet/desktop)

---

## 📁 Project Structure

```
.
├── frontend/ (React)
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── App.js
│   │   └── index.js
├── backend/
│   └── app.py
└── inventory.db (auto-created)
```

---

## ⚙️ Setup Instructions

### 🖥 Backend (Flask + SQLite)

```bash
cd backend
pip install flask flask-cors
python app.py
```

### 💻 Frontend (React)

```bash
cd frontend
npm install
npm start
```

> Make sure the backend runs on port `5000` and frontend on `3000` for CORS to work smoothly.

---

## 🧪 Sample Queries & Results

| User Query         | Bot Response Sample                          |
|--------------------|----------------------------------------------|
| `books`            | Atomic Habits, The Alchemist, Zero to One... |
| `product 1`        | Product 1                                     |
| `zero to one`      | Zero to One                                   |
| `show all`         | All 100 products returned                    |
| `electronics`      | iPhone 14 Pro, Dell XPS 15, AirPods Pro       |