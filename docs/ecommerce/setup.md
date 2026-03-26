# 🛠️ Setup Guide (Step-by-Step)

This guide will help you install everything and run the project.

---

##  Step 1: Install Required Software

### 1. Install Node.js

Download and install Node.js (v18+)

Check:

```bash
node -v
npm -v
```

---

### 2. Install Python

Install Python (v3.10+)

Check:

```bash
python --version
```

---

### 3. Install Git

Used for downloading project code

Check:

```bash
git --version
```

---

## 📁 Step 2: Clone the Project

```bash
git clone https://github.com/BoopathiKumar6485/test_MK_docs.git
cd project
```

---

# 🎨 FRONTEND SETUP (React + Vite)

##  Step 3: Install Frontend

```bash
cd frontend
npm install
```

---

## ▶ Step 4: Start Frontend Server

```bash
npm run dev
```

 Open:
http://localhost:5173/

---

# ⚙️ BACKEND SETUP (FastAPI)

## 📦 Step 5: Go to Backend

```bash
cd ../backend
```

---

## 🧪 Step 6: Create Virtual Environment

```bash
python -m venv venv
```

Activate:

### Windows:

```bash
venv\Scripts\activate
```

---

##  Step 7: Install uv

```bash
pip install uv
```

---

##  Step 8: Install Dependencies

```bash
uv pip install fastapi uvicorn pydantic
```

---

## ▶️ Step 9: Start Backend Server

```bash
uvicorn main:app --reload
```

👉 Open:
http://127.0.0.1:8000/

👉 API Docs:
http://127.0.0.1:8000/docs

---

#  DATABASE SETUP

##  Step 10: SQLite (Default)

👉 No need to install
👉 Works automatically

---

## 🔄 Step 11: PostgreSQL (Later Upgrade)

Install PostgreSQL and update connection string in code.

---

# 📘 DOCUMENTATION SETUP (MkDocs)

##  Step 12: Install MkDocs

```bash
pip install mkdocs
```

---

##  Step 13: Create Docs

```bash
mkdocs new my-docs
cd my-docs
```

---

## ▶️ Step 14: Run Docs Server

```bash
mkdocs serve
```

👉 Open:
http://127.0.0.1:8000/

---

## 🎨 Step 15: Install Theme

```bash
pip install mkdocs-material
```

Edit `mkdocs.yml`:

```yaml
theme:
  name: material
```

---

#  Final

Now you have:

* Frontend running (React)
* Backend running (FastAPI)
* Database working (SQLite)
* Documentation site (MkDocs)

---

##  Congratulations!

You successfully built and ran a full-stack project 🚀
