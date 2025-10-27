📌 GrabIt – Online Food Ordering System

A simple and efficient web-based food ordering platform built using Django, MySQL, and Bootstrap-5. GrabIt allows users to browse food categories, explore dishes, add items to cart, and place their orders with a seamless shopping experience.

✅ Features

✔ User Authentication (Login/Register)
✔ Fully Responsive UI with Bootstrap
✔ Browse Food Categories & Items
✔ Dynamic Food Detail Page
✔ Add to Cart with Quantity Update
✔ Remove Items from Cart
✔ Trending Food Section
✔ Django Admin Panel for Managing Products & Categories
✔ Secure CSRF-enabled requests
✔ Real-time Cart Updates using Fetch API

🛠️ Technologies Used
Component	Technology
Frontend	HTML5, CSS3, Bootstrap 5, JavaScript
Backend	Django (Python)
Database	MySQL
ORM	Django ORM
Server	Django Development Server
Auth	Django Authentication System
🧩 Core Modules
Module	Description
Home	Displays trending food and promotional images
Categories	Lists all available food categories
Food Detail Page	Detailed description, price, vendor, stock & add to cart
Cart	Shows all selected items with price updates
Authentication	Register/Login/Logout
Admin Dashboard	Add food items, categories & manage users
📂 Project Structure
📦 GrabIt
├─ shop
│  ├─ templates/shop
│  ├─ static
│  ├─ models.py
│  ├─ views.py
│  ├─ urls.py
├─ GrabItProject
│  ├─ settings.py
│  ├─ urls.py
├─ media/
└─ db.sqlite3 / MySQL Database

⚙️ Installation Guide
1️⃣ Clone the repository
git clone https://github.com/yourusername/grabit.git
cd grabit

2️⃣ Create Virtual Environment & Install Dependencies
python -m venv env
env\Scripts\activate  # for Windows
pip install -r requirements.txt

3️⃣ Database Configuration

In settings.py configure MySQL:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'grabit_db',
        'USER': 'root',
        'PASSWORD': 'yourpassword',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}


Apply migrations:

python manage.py migrate

4️⃣ Create Superuser for Admin Panel
python manage.py createsuperuser

5️⃣ Run the server
python manage.py runserver


Access the app at:
👉 http://127.0.0.1:8000/

Access Admin Panel at:
👉 http://127.0.0.1:8000/admin/

🪄 Screenshots (Add Yours)
Screen	Description
✅ Home Page	Food carousel + trending dishes
✅ Categories Page	Food grouped by category
✅ Cart Page	Shows selected food items

Add images inside /static/images/screenshots/ and reference them in README.

🚀 Future Enhancements

🔹 Online payment gateway (UPI / Cards)
🔹 Order Tracking System
🔹 User Profile & Order History
🔹 Wishlist Feature
🔹 Live stock updates
🔹 Razorpay / Stripe Integration
