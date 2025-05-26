# 🛍️ Django eCommerce Website

A simple and functional eCommerce web application built using Django. This project allows users to browse products, manage their cart, and complete orders. It also includes basic admin features for managing inventory.

## 🔧 Tech Stack
- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite

## ✨ Features
- User registration and login system
- Product listing with categories
- Add to cart and remove from cart functionality
- Order summary and checkout
- Admin panel for managing products

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/atulguptag/Django-eCommerce-Website.git
cd Django-eCommerce-Website
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (for admin access)
```bash
python manage.py createsuperuser
```

### 6. Start the Server
```bash
python manage.py runserver
```

Now go to `http://127.0.0.1:8000/` to see the app running!

## 📁 Project Structure
- `store/` - Core eCommerce logic (models, views, URLs)
- `templates/` - HTML templates for the app
- `static/` - CSS, JS, images

## 📝 Note
This is a learning project aimed at understanding how to build a basic eCommerce site with Django. Feel free to improve the design, add payment gateways, or enhance the product management features!

---

## 📫 Contact
Made  by [Lovish Tuteja](https://github.com/Lovish-t)
