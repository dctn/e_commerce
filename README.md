# 🛍️ Django E-Commerce Project

A simple and scalable e-commerce platform built with **Django**.
This project demonstrates user authentication, product management, and order handling with a clean structure — perfect for learning or extending into production.

---

## 🚀 Features

* User registration & login (with Django auth)
* Product listing and details page
* Shopping cart and checkout flow
* Order tracking
* Admin management for products, users, and orders
* Modular app structure with templates and static files

---

## 🧩 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap (extendable)
* **Database:** SQLite (default) or PostgreSQL/MySQL
* **Environment Management:** [uv](https://docs.astral.sh/uv/) or virtualenv

---

## ⚙️ Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/dctn/e_commerce.git
cd e_commerce
```

---

### 2. (Option A) Setup Using `uv` (Recommended)

```bash
pip install uv
uv venv
```

Activate environment:

```bash
# Windows
.venv\Scripts\activate
# Linux/Mac
source .venv/bin/activate
```

Install dependencies:

```bash
uv pip install -r requirements.txt
```

---

### 2. (Option B) Setup Using Regular `pip`

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

---

### 3. Apply Migrations

```bash
python manage.py migrate
```

---

### 4. Run the Development Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000
```

---


## 🗂️ Project Structure

```
e_commerce/
│
├── manage.py
├── requirements.txt
├── README.md
│
├── e_commerce/            # Project settings & URLs
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── store/                 # Main app (products, cart, orders)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── static/
│
└── users/                 # Authentication-related views
```

---

## 🧾 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

---

**Author:** [dctn](https://github.com/dctn)
**Project:** [E-Commerce Django App](https://github.com/dctn/e_commerce)
