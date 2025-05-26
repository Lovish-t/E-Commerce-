# 🛍️ Django eCommerce Website

This is a simple online shopping website made using Django. It lets users look at products, add them to a cart, and place orders. There's also an admin panel to add or manage products.

## 🔧 Built With
- Python & Django
- HTML, CSS, JavaScript
- SQLite (default database)

## ✨ What It Can Do
- Sign up and log in as a user
- Browse products by category
- Add to cart and checkout
- Admin can add/edit/delete products

## 🚀 How to Run

1. **Clone the repo**
```bash
git clone https://github.com/atulguptag/Django-eCommerce-Website.git
cd Django-eCommerce-Website
```

2. **Set up a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install the packages**
```bash
pip install -r requirements.txt
```

4. **Run the migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Make an admin user**
```bash
python manage.py createsuperuser
```

6. **Start the website**
```bash
python manage.py runserver
```

Go to your browser and open: `http://127.0.0.1:8000/`

## 📁 Folders You’ll See
- `store/` – All the website code (models, views, urls)
- `templates/` – HTML files
- `static/` – CSS and JS files

## 👨‍💻 About
This was made to practice Django and understand how online stores work.

---

Made by [Lovish Tuteja](https://github.com/Lovish-t)
