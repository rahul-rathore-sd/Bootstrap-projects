# 🚀 Rahul's Project Collection

Welcome to my repository of **web development projects** — built using technologies like **HTML, CSS, JavaScript, React, PHP, Django, Laravel, and Node.js**.  
Each project showcases different features, functionality, and clean code implementation.

---

## 🧩 Table of Contents
- [About](#about)
- [Projects](#projects)
- [Tech Stack](#tech-stack)
- [How to Run Locally](#how-to-run-locally)
- [Contact](#contact)

---

## 📖 About

This repository contains all my personal and learning-based projects.  
Each project folder includes:
- 📁 Full project source code  
- 🧠 Explanation of features  
- 💡 Example code snippets  
- ⚙️ Setup instructions  

---

## 💼 Projects

### 🛒 1. **E-Commerce Website (Django + React)**
A full-stack e-commerce web app with user authentication, product management, cart, checkout, and admin panel.

**✨ Features**
- User signup/login with profile image  
- Product list with images and videos  
- Cart, checkout, and order history  
- Admin panel to manage users and orders  
- PostgreSQL database integration  

**🧰 Tech Stack**
`React` • `Django` • `PostgreSQL` • `Bootstrap` • `REST API`

**💻 Code Example**
```python
# models.py
class Product(models.Model):
    name = models.CharField(max_length=100)
    price = models.DecimalField(max_digits=8, decimal_places=2)
    image = models.ImageField(upload_to='products/')
