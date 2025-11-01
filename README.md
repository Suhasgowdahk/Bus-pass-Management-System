# 🚌 Bus Pass Management System (DBMS Project)

The **Bus Pass Management System** is a database-driven web application built using **PHP** and **MySQL**, designed as a **DBMS mini project**.  
It helps automate the process of issuing, renewing, and managing bus passes efficiently through a centralized database.

---

## 🎯 Project Objective

To design and implement a **Database Management System** that simplifies and digitalizes the bus pass issuance process, allowing users to apply, renew, and track passes while enabling administrators to manage all records from a single interface.

---

## 🧩 Key Features

- 🧾 **User Management:** Register, login, and update user profiles.  
- 🚌 **Bus Pass Application:** Apply online for new or renewal of passes.  
- 💾 **Database Integration:** All operations stored and managed in **MySQL**.  
- 🔍 **Search & Filter:** Retrieve user or pass data efficiently.  
- 🧍‍♂️ **Admin Dashboard:** Approve, reject, or update bus pass details.  
- 📊 **Report Generation:** View pass and route statistics (optional).  

---

## 🛠️ Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | HTML5, CSS3 |
| **Backend** | PHP |
| **Database** | MySQL |
| **Server** | XAMPP (Apache + MySQL) |

---

## 🗄️ Database Design

**Database Name:** `buspassdb`

**Main Tables:**
1. `users` – Stores user registration details  
2. `bus_pass` – Contains issued pass information  
3. `routes` – Manages bus route and fare details  
4. `admin` – Admin login and credentials  
5. `payments` *(optional)* – For storing Razorpay or manual payment logs  

> 💡 The database uses **foreign key relationships** between `users` and `bus_pass` for relational integrity.

---

## ⚙️ Installation Steps

### 1️⃣ Download & Extract
- Download the ZIP file and extract it.  
- Copy the **`buspassms`** folder.

### 2️⃣ Move to XAMPP Directory
- Paste it inside:
C:\xampp\htdocs\


### 3️⃣ Configure Database
- Open **phpMyAdmin** → [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Create a database:
buspassdb
- Import the SQL file located in:
SQL File/buspassdb.sql

### 4️⃣ Run the Project
Open your browser and go to:
http://localhost/buspassms

---

## 🧑‍💻 Default Credentials

| Role | Username | Password |
|------|-----------|-----------|
| Admin | admin | admin123 *(update if changed)* |

---

## 🧮 ER Diagram (Suggested)
If your project submission requires it, include an **ER Diagram** showing relationships between:
Users → Bus_Pass → Routes
↘ Payment
*(You can design it in draw.io or MySQL Workbench.)*

---

## 🚀 Future Improvements

- Integration with online payment APIs (Razorpay)  
- Automatic email notifications for pass renewal  
- QR code-based bus pass verification  
- Enhanced analytics dashboard  

---

## 📚 Academic Context

This project was developed as part of the **Database Management Systems (DBMS)** course to demonstrate database modeling, relational integrity, and CRUD operations through a web-based system.

---

## 📬 Contact

**Developer:** Suhas H K  
📧 Email: [suhashk778@gmail.com](mailto:suhashk778@gmail.com)

---

## 📝 License

This project is open-source under the **MIT License**.

---
