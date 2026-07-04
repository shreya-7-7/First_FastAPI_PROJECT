````markdown
<div align="center">

# 🚀 First FastAPI Project

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/FastAPI-API-009688?style=for-the-badge&logo=fastapi"/>
<img src="https://img.shields.io/badge/Deployment-Render-46E3B7?style=for-the-badge&logo=render"/>
<img src="https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge"/>

### 🌱 My First FastAPI API

*A simple FastAPI application built to learn the fundamentals of creating and deploying APIs.*

---

</div>

# 📖 About This Project

This project is my first FastAPI application. It demonstrates how to create a basic API endpoint, run the application locally using Uvicorn, and deploy it successfully on Render.

---

# 🌐 Live Demo

**Live API:** https://first-fastapi-project-k0te.onrender.com

| Method | Endpoint | URL |
|--------|----------|-----|
| GET | `/` | https://first-fastapi-project-k0te.onrender.com/ |

### Sample Response

```json
{
    "message": "Hello from FastAPI"
}
```

---

# ✨ Features

- 🚀 FastAPI application setup
- 📡 Basic GET endpoint
- 📖 Automatic API documentation
- ☁️ Deployed on Render

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Programming Language |
| ⚡ FastAPI | Web Framework |
| 🚀 Uvicorn | ASGI Server |
| ☁️ Render | Deployment Platform |

---

# 📂 Project Structure

```text
First_FastAPI_PROJECT/
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 💻 Source Code

```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def home():
    return {
        "message": "Hello from FastAPI"
    }
```

---

# ▶️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone <your-repository-url>
```

### 2️⃣ Navigate to the Project

```bash
cd First_FastAPI_PROJECT
```

### 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 6️⃣ Run the Application

```bash
uvicorn app:app --reload
```

---

# 📖 API Documentation

After running the application locally:

### Swagger UI

```text
http://127.0.0.1:8000/docs
```

### ReDoc

```text
http://127.0.0.1:8000/redoc
```

---

# 📈 Progress

- [x] FastAPI Setup
- [x] First API Endpoint
- [x] Local Testing
- [x] Deployment on Render

---

<div align="center">

**Happy Coding! 🚀**

</div>
````
