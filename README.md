# Flask E-Commerce Website

A modular Flask-based e-commerce web application with essential functionalities such as product listings, cart management, and customer handling.

##  Project Structure
  ecommerce-project/
  ├── admin/ # Admin-related logic
  ├── carts/ # Shopping cart logic
  ├── customers/ # Customer accounts, login, signup
  ├── products/ # Product and category management
  ├── shop/ # Core app integrating all components
  ├── static/ # CSS, JS, Images
  ├── templates/ # HTML templates for rendering views
  ├── requirements.txt
  ├── requirement.text # (typo, same as requirements.txt)
  └── run.py # Project entry point


---

##  Features

###  Customers
- Sign Up / Sign In
- Browse products
- Add to cart
- Checkout

###  Admin
- Login via `/admin`
- Add/Edit/Delete products and categories
- Manage orders and customer data

###  Technologies Used
- **Backend:** Flask
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite3,Sqlalchemy

---

## Set Up a Virtual Environment
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install Dependencies
  pip install -r requirements.txt
   Note: requirement.text is a duplicate; use only requirements.txt.

## Run Migrations
  python run.py makemigrations
  python run.py migrate

## Create Superuser
  python run.py createsuperuser

## Start the Server 
python run.py runserver
Then visit: http://127.0.0.1:8000/

 ## License
This project is for educational/demo use. MIT License

