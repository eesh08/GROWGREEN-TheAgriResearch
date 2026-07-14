GROWGREEN – Agriculture E-Commerce Platform
GROWGREEN is a full-stack Web application connecting farmers and cosumers making grocery purchase easier 
It includes complete product management, order handling, authentication, and an admin dashboard for store operations.
🚀 Features
User Features
Browse products by category (fertilizers, pesticides, tools, fruits, vegetables, etc.)
Add products to cart and place orders
User signup/login & profile management
View order history and booking details
Admin Features
Admin authentication
Add/Edit/Delete:
Categories
Products
Bookings
Users
View all orders and order details
Date-based booking reports
Technical Features
Django models, views, templates (MVT architecture)
Static files management (CSS, JS, images)
SQLite database
Form handling & validations
Dynamic pages powered by Django template engine
🏗️ Project Structure
growgreenfinal/        # Main Django project
    settings.py
    urls.py
    wsgi.py

grocery/               # Main application
    models.py
    views.py
    urls.py
    templates/
    static/
    migrations/

media/                 # User-uploaded images (if enabled)
📦 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/eesh08/GROWGREEN--The-Agri-Reasearch.git
cd GROWGREEN--The-Agri-Reasearch
2️⃣ Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Apply migrations
python manage.py migrate
5️⃣ Run the development server
python manage.py runserver
🔑 Default Admin Login (if you created one)
/admin
username: admin
password: *****
🛠️ Tech Stack
Backend: Django, Python
Database: SQLite
Frontend: HTML, CSS, Bootstrap, JavaScript
Tools: Django Template Engine, Static & Media Handling
📸 Screenshots (Optional Section)
(Add later once your app is stable)
🤝 Contributions
Not open for public contributions currently.
📄 License
This project is for educational and demo purposes.
Deployment link- http://growgreenagriresearch.com
