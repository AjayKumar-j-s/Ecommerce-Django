# Ecommerce-Django
This project is a fully functional e-commerce web application built using Python Django framework with a focus on scalable backend architecture, robust database design, and modular application structure. 
It provides core functionalities expected in modern online stores such as user management, product browsing, cart and favorites handling, 
category-wise navigation, and stock control, while ensuring maintainability and extendability.
The backend is integrated with MySQL for structured data handling and uses Pillow for image uploads, with enhanced admin interface via Jazzmin. All views are dynamic and follow Django’s MVC (Model-View-Controller) paradigm.


🧰 Tech Stack:
Backend Framework: Django (Python)

Database: MySQL

Environment Management: pipenv

Media Handling: Pillow

Admin Theming: Jazzmin

Template Engine: Django Templates


Templates

🚀 Key Features Implemented:
MySQL Database integration via settings.py

Project & app-level URL routing (urls.py)

Dynamic template rendering with category and product data

Models for Category, Product, Cart, and Favourite

Image uploading and storage using Django ImageField and Pillow

Admin panel customization with Jazzmin

Category-wise product listing and filtering

Trending & out-of-stock product indicators

Breadcrumb-based page navigation

Django user registration, login/logout system

Django flash messages for alerts using Bootstrap

Add to Cart and Favourite features with session handling

Data fetched directly from the database with ORM queries

🔧 Management Commands Used:
pipenv install django

python manage.py makemigrations and migrate

python manage.py createsuperuser

Custom model registration in admin.py



