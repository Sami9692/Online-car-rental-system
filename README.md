# Online-car-rental-system

The **Online Car Rental System** is a full-stack web application that allows users to easily browse, book, and rent cars online. It simplifies the rental process by providing an interactive and efficient platform for customers and administrators to manage bookings, payments, and vehicle availability digitally.

---

## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Overview](#-project-overview)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Contributors](#-contributors)
- [License](#-license)

---

## ✨ Features

- 🧑‍💻 **User Authentication** – Secure registration and login for users and admins  
- 🚘 **Car Management** – Admins can add, edit, or delete car listings  
- 📅 **Online Booking** – Real-time vehicle booking and rental scheduling  
- 💳 **Payment Integration** – Simplified and secure online payment for bookings  
- 📜 **Booking History** – Users can view previous and active rentals  
- 📱 **Responsive Design** – Works across mobile, tablet, and desktop devices  
- 🔒 **Session Management** – Ensures user security and proper session handling  

---

## 🛠️ Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | Python (Flask Framework) |
| **Database** | MySQL |
| **Libraries/Modules** | Flask-Session, Werkzeug, Flask-MySQLdb |
| **Server** | Localhost (XAMPP or MySQL Workbench) |

---

## 📖 Project Overview

The system allows customers to:
- Register and log in to the platform  
- Browse available cars  
- Book cars for specific dates and durations  
- Make payments securely  

The admin can:
- Manage car listings (add, edit, delete)  
- View all bookings and users  
- Approve or cancel rental requests  

This project aims to **automate manual car rental operations** and provide a **digital, efficient, and secure** rental experience.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```
git clone https://github.com/<your-username>/online-car-rental-system.git
cd online-car-rental-system
```
### 2️⃣ Create and Activate Virtual Environment
```
python -m venv venv
# For Windows
venv\Scripts\activate
# For Linux/Mac
source venv/bin/activate
```

### 3️⃣ Install Required Dependencies
```
pip install -r requirements.txt
```

### 4️⃣ Configure the Database

Create a MySQL database (e.g., car_rental_db)

Import the provided SQL file 

Update database credentials in your Flask config file

### 5️⃣ Run the Application
```
python app.py
```

