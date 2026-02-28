📘 Smart-Mart – Technical Documentation
1️⃣ Introduction

Smart-Mart is a full-stack web-based e-commerce application developed to provide a seamless online shopping experience, particularly focusing on rural and small-scale markets. The system enables users to browse products, manage carts, and securely complete transactions using Razorpay payment integration.

The application is built using Django (Python) for backend processing, MySQL for data storage, and HTML/CSS/JavaScript for the frontend interface.

2️⃣ Problem Statement

Traditional rural markets often lack digital infrastructure, making it difficult for small vendors and customers to engage in online commerce. Existing e-commerce platforms may not always be optimized for small-scale business integration.

Smart-Mart addresses this issue by:

Providing a lightweight e-commerce solution

Enabling secure digital payments

Supporting product management and user authentication

Offering a simple and intuitive interface

3️⃣ System Architecture

The application follows a three-layer architecture:

🔹 Presentation Layer

HTML templates

CSS styling

JavaScript for interactivity

🔹 Application Layer

Django views

Business logic

Cart and order management

Razorpay payment processing

🔹 Data Layer

MySQL database

User accounts

Product records

Order details

4️⃣ Functional Requirements
4.1 User Authentication

User registration

Secure login/logout

Session handling

4.2 Product Management

Product listing

Product images

Category organization

4.3 Cart Management

Add to cart

Remove from cart

Update quantity

Calculate total price

4.4 Payment Integration

Razorpay checkout integration

Payment verification

Success and failure handling

4.5 Order Summary

Display purchased items

Payment confirmation

Transaction details

5️⃣ Non-Functional Requirements

Secure password handling

Fast page load performance

Clean and responsive UI

Reliable database transactions

Error handling for failed payments

6️⃣ Database Design

The system stores:

User information

Product details

Cart items

Order history

Payment records

MySQL is used as the relational database to maintain structured data with relationships between users, products, and transactions.

7️⃣ Project Structure
Smart-Mart/
│
├── smartmart/          # Main Django project
├── sm_app/             # Core application logic
├── templates/          # HTML templates
├── static/             # CSS, JS, images
├── media/              # Uploaded product images
├── manage.py           # Django entry point
8️⃣ Payment Workflow

User adds products to cart

Proceeds to checkout

Razorpay checkout is initialized

User completes payment

System verifies payment response

Order summary page is displayed

9️⃣ Security Considerations

Razorpay secure API usage

Password authentication via Django

CSRF protection

Input validation

Secure database queries

🔟 Future Enhancements

Email notifications

Order tracking system

Admin analytics dashboard

Mobile responsive improvements

Vendor panel for product management

📌 Conclusion

Smart-Mart demonstrates the implementation of a scalable and secure e-commerce platform using Django and MySQL. The integration of Razorpay ensures reliable online transactions, while the modular architecture allows for future expansion and feature enhancements.

This project highlights full-stack development skills, payment gateway integration, and practical implementation of real-world e-commerce workflows.
