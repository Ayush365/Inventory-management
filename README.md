# 📦 Smart Inventory API

A simple and efficient **Inventory Management REST API** built using **FastAPI** and **SQLite**.
This project provides basic CRUD operations to manage inventory items.

---

## 🚀 Features

* Add new inventory items
* View all items
* Update item details
* Delete items
* Lightweight SQLite database
* Clean modular architecture (Router → Service → DB)

---

## 🛠️ Tech Stack

* **Backend:** FastAPI
* **Database:** SQLite
* **ORM:** SQLAlchemy
* **Language:** Python 3

---

## 📂 Project Structure

```
Inventory_management/
│
├── app/
│   ├── main.py              # Entry point
│   ├── database/           # DB connection
│   ├── models/             # SQLAlchemy models
│   ├── schemas/            # Pydantic schemas
│   ├── routers/            # API routes
│   └── services/           # Business logic
│
├── inventory.db            # SQLite database
├── requirements.txt        # Dependencies
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create virtual environment

```bash
python -m venv venv
```

### 3. Activate environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/Mac:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Server

```bash
uvicorn app.main:app --reload
```

Server will start at:

```
http://127.0.0.1:8000
```



## 📖 API Documentation

FastAPI provides built-in docs:

* Swagger UI:
  `http://127.0.0.1:8000/docs`

* ReDoc:
  `http://127.0.0.1:8000/redoc`

---

## 🧠 Notes

* Database is automatically created on first run
* Uses layered architecture for scalability
* Easily extendable (authentication, pagination, etc.)

---

## 📜 License

This project is open-source and free to use.

---

## 👨‍💻 Author

Developed as a Computer Science project for learning backend API design.
