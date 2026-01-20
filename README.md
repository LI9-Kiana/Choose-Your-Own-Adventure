# 🧙 Interactive Story Generator

An AI-powered **choose-your-own-adventure** web application that generates interactive stories based on a user-provided theme. Users can explore branching storylines, make choices, reach different endings, and restart or generate new stories at any time.

---

## ✨ Features

- 🎨 Generate stories from a custom theme
- 🌳 Interactive branching narrative (choose-your-own-adventure)
- 🏁 Multiple endings (including winning endings)
- 🔁 Restart story or generate a new one
- ⚡ Fast frontend with Vite + React
- 🚀 Backend API built with FastAPI
- 🗄️ SQLite database for story persistence

---

## 🏗️ Tech Stack

### Frontend
- React
- Vite
- React Router
- Axios

### Backend
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

---

## 📁 Project Structure

```text
Choose_Your_Own_Adventure/
│
├── backend/
│   ├── main.py
│   ├── routers/
│   ├── models/
│   ├── database.db
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── util.js
│   │   └── App.jsx
│   ├── vite.config.js
│   └── package.json
│
└── README.md


```
---

## 🚀 Future Improvements

- User accounts and saved stories
- Story graph / tree visualization
- Improved ending summaries
- UI theming and customization