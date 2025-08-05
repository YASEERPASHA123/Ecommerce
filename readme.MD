# 🛒 ZippyCart - Django eCommerce Website

**ZippyCart** is a dynamic and user-friendly **Django-based eCommerce web application** that enables users to browse products, add them to a cart (using `localStorage` for speed and flexibility), securely register and log in through **100% email verification**, and track their order status via a personal profile dashboard. The admin panel allows easy delivery status updates. 

This project is ideal for learning how to build full-stack web applications using Django, including secure authentication, static media handling, and deployment best practices.

---

## 🚀 Features

### 🧑‍💻 User-Facing Features:
- 🛒 **Add-to-Cart** system powered by browser `localStorage` – fast and doesn't require login.
- 📝 **User Registration with Email Verification** – users must confirm their email to activate the account.
- 🔐 **Login/Logout Authentication** – securely managed using Django sessions.
- 📦 **Order Tracking System** – users can view order status and history in their profile.

### 🛠️ Admin Features:
- 📤 **Update Order Delivery Status** – easily update user orders from Django Admin.
- 🧾 **View All Orders** – full access to customer orders for backend management.

### 🔒 Security and Configuration:
- ✅ **100% Email Verification System** – ensures only verified users can access the platform.
- 🧬 **Environment Variable Support via `.env`** – sensitive information like `SECRET_KEY` and email credentials are kept safe and out of source control.
- 🚫 **`.env` is excluded from GitHub** using `.gitignore`.

---

## 💻 Tech Stack

| Layer        | Technologies                              |
|--------------|--------------------------------------------|
| Backend      | Python, Django 3.2                         |
| Frontend     | HTML5, CSS3, Bootstrap, JavaScript         |
| Database     | SQLite (Default, easy for development)     |
| Authentication | Django’s built-in auth + email verification |
| Email Engine | SMTP (e.g., Gmail)                         |
| Hosting (optional) | Render, Heroku, PythonAnywhere (not included here) |
| Version Control | Git & GitHub                           |

---

