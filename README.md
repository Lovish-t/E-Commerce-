# Django eCommerce Website

This is a basic online shopping website made using Django. It lets users look at products, add them to a cart, and place an order. There is also an admin panel to manage the products.

## What I used
- Python and Django
- HTML, CSS, JavaScript
- SQLite (default database)

## What it can do
- Users can register and log in
- They can see products and add them to the cart
- They can place an order
- Admin can add, edit, or delete products

## How to run it

1. First, clone this project
```
git clone https://github.com/atulguptag/Django-eCommerce-Website.git
cd Django-eCommerce-Website
```

2. Make a virtual environment and activate it
```
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

3. Install the packages
```
pip install -r requirements.txt
```

4. Run the migrations
```
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser (admin)
```
python manage.py createsuperuser
```

6. Start the server
```
python manage.py runserver
```

Then open your browser and go to: http://127.0.0.1:8000/



## About
I made this project to learn how Django works and how eCommerce websites are made.

Made by Lovish Tuteja - https://github.com/Lovish-t
