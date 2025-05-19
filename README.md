# 🗃️ Inventory Management System

A simple and functional **Inventory Management System** built using **Flask**, **SQLite**, **SQLAlchemy**, and basic **HTML/CSS**. This project enables users to manage inventory items securely with full CRUD capabilities and user authentication.

---

## 📌 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [License](#-license)

---

## ✅ Features

- 🔐 **User Authentication** (Register/Login/Logout)
- 📄 **CRUD Operations** on Inventory Items
- 🧩 **Flask with SQLAlchemy ORM**
- 🗂️ **SQLite** Database (auto-generated on first run)
- 🖥️ **Simple UI** with basic CSS
- 🛡️ **Protected Routes** using Flask-Login

---

## 🛠️ Tech Stack

| Category       | Technology      |
|----------------|-----------------|
| Backend        | Python (Flask)  |
| Database       | SQLite (via SQLAlchemy) |
| Authentication | Flask-Login     |
| Frontend       | HTML, CSS       |
| Package Mgmt   | pip             |

---

## 🖼️ Screenshots

> 💡 Add screenshots here after running the project.

![Login Page](screenshots/login.png)
![Dashboard](screenshots/dashboard.png)
![Add Item](screenshots/add_item.png)

---

## 📁 Project Structure

```
inventory-management-system/
├── app.py
├── requirements.txt
├── /templates
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── add_item.html
│   └── edit_item.html
├── /static
│   └── /css
│       └── styles.css
├── /instance
│   └── database.db (auto-created)
└── README.md
```

---

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/inventory-management-system.git
   cd inventory-management-system
   ```

2. **Set Up Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate        # For Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python app.py
   ```

---

## 🌐 Usage

- Visit: `http://127.0.0.1:5000/`
- Register a new user.
- Log in using your credentials.
- Add, update, or delete inventory items.
- All operations are secured and require login.

---

## 🧠 Future Enhancements

- 🔍 Search & Filter items
- 📊 Add item categories and analytics (e.g., Chart.js)
- 📤 Export inventory to Excel/CSV
- 🧑‍💼 Role-based access (Admin/User)
- 🖼️ Upload item images

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 💬 Feedback

Feel free to contribute or suggest improvements via pull requests or issues!
