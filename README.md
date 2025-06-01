# 🚗 Vehicle Management System (DBMS Project)

## 📋 Project Overview

The **Vehicle Management System** is a relational database project developed using SQL and PL/SQL. It is designed to efficiently manage data related to users, vehicles, parking slots, bookings, and payments. The system ensures data consistency, supports advanced data retrieval, and includes automation using PL/SQL.

---

## 🛠️ Technologies Used

- **Database:** MySQL / Oracle  
- **Language:** SQL, PL/SQL  
- **Tools:** MySQL Workbench / Oracle SQL Developer

---

## 🧱 Database Schema

The project includes the following normalized tables:

1. `User` – (USER_ID, USER_NAME, MOBILE, PASSWORD, AGE)  
2. `Vehicle` – (V_ID, COLOUR, BRAND, PLATE_NUMBER, MODEL, VEHICLE_TYPE)  
3. `Vehicle_Owner` – (O_ID, OWNER_NAME, AGE, MOBILE, ADDRESS)  
4. `Parking_Slot` – (SLOT_ID, LOCATION, USER_ID, QUALITY, FLOOR)  
5. `Booking` – (B_ID, V_ID, SLOT_ID, USER_ID, PAID_BY, BOOKING_DATE, DUE)  
6. `Payment` – (P_ID, B_ID, USER_ID, PAID_BY, PAID_AMOUNT, PAYMENT_DATE)

---

## 🌟 Key Features

- 🔗 **Normalized schema** with 6 interrelated tables  
- 🔍 **Advanced SQL** queries: JOINs, filters, and nested subqueries  
- ⚙️ **PL/SQL features**: procedures, functions, triggers, cursors, and exception handling  
- 📊 **Reports and search** based on user, booking, payment, and vehicle data  
- 🔐 **Role-based access** and data integrity enforced through constraints

---

## 📥 Sample Data

Each table is populated with **10+ rows** to simulate real-world operations.

---

## 🔎 Query Types Implemented

### a) **Search from Single Table (10+ Queries)**  
- Filter by vehicle brand, user age, parking floor, payment method, etc.

### b) **Search from Multiple Tables (5+ JOINs)**  
- Booking info with vehicle and user data  
- Payment report with booking details  
- Owner and vehicle mapping

### c) **Subqueries**  
- Nested, correlated, and aggregate subqueries for reporting and filtering

### d) **PL/SQL (5 Types)**  
- **Stored Procedure** – Insert booking data  
- **Function** – Calculate total payments by user  
- **Trigger** – Auto-update dues  
- **Cursor** – Loop through booking history  
- **Exception Handling** – Handle duplicate and null entries

---

## 📂 How to Use

1. Import schema and create all tables in MySQL or Oracle.
2. Insert sample data using provided SQL `INSERT` statements.
3. Execute query files to test all use cases.
4. Run PL/SQL scripts for automation and validation.

---

## 👨‍💻 Author

**Alfaz Uddin Emon**  
Department of CSE, IIUC  


---

## 📄 License

This project is for educational purposes only.
