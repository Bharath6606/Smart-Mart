🛒 Smart-Mart

A Web-Based E-Commerce Platform for Rural Markets

📌 Project Overview

Smart-Mart is a full-stack e-commerce web application designed to support rural users and small vendors with a seamless online shopping experience. It provides a complete shopping workflow including user registration, product browsing, cart management, and secure checkout using Razorpay integration. The system is built using Django for backend processing, MySQL for data storage, and a responsive frontend for intuitive user interaction.

🚀 Key Features

🔐 User Authentication – Secure login and registration

🛍️ Product Catalogue – Browse and search products

🛒 Cart System – Add, update, and remove items

💳 Payment Integration – Seamless checkout via Razorpay

📦 Order Summary Page – Displays detailed order information

📁 Media Management – User-friendly product image handling

🧠 How It Works

Users sign up or log in to their account.

They browse available products and add desired items to the cart.

Once ready, users proceed to checkout.

The system integrates with Razorpay to securely process payments.

Upon successful payment, the user is shown an order summary with all relevant details.

🛠️ Tech Stack
Component	Technology
Backend	Python, Django
Frontend	HTML, CSS, JavaScript
Database	MySQL
Payment Gateway	Razorpay
Deployment	GitHub, local testing
📁 Project Structure
smartmart/
├── media/  
├── sm_app/  
├── static/
├── templates/
├── manage.py

media/ — Uploaded images and media files

sm_app/ — Main Django app

static/ — CSS, JS, and image assets

templates/ — HTML templates

manage.py — Django project entry point

🧩 Screenshots

(Optional — Upload screenshots in an images/ folder and embed below)

![Homepage](images/homepage.png)
![Product page](images/products.png)
📦 Installation & Setup
Clone the repository
git clone https://github.com/Bharath6606/Smart-Mart.git
cd Smart-Mart
Create virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate
Install dependencies
pip install -r requirements.txt
Configure database

Update your MySQL credentials in:

smartmart/settings.py

Run migrations:

python manage.py makemigrations
python manage.py migrate
Run the application locally
python manage.py runserver
🧾 Payment Integration

This project integrates Razorpay for seamless online payments. Ensure you add your Razorpay API keys in keys.py or environment variables.

🙌 Future Enhancements

🔔 Order notifications via email or SMS

📱 Mobile responsive UI improvements

📊 Analytics dashboard for vendors

🗂️ User profile with order history

👨‍💻 Developer

Devi Bharadvaj
Computer Science & Engineering (AIML)
📧 devibharadvaj06@gmail.com

🔗 https://github.com/Bharath6606

📜 License

This project is open-source and free to use. Contributions and improvements are welcome.
