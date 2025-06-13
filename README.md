# ☕ Café Management System

A simple and efficient **Café Management System** developed using **VB.NET** (Windows Forms) and **SQL Server**. This desktop application helps streamline café operations including menu management, order processing, billing, and customer tracking.



## 📌 Features

- 🧾 **Order Management** – Take and manage customer orders with ease.
- 🍽️ **Menu Management** – Add, update, or delete menu items including categories (drinks, snacks, meals).
- 💵 **Billing System** – Automatic calculation of totals, taxes, and bill generation.
- 👥 **Customer Management** – Track regular customers and their preferences.
- 📦 **Inventory Management** – Manage ingredients and stock levels.
- 🔒 **Authentication System** – Secure login system for Admin and Staff.
- 📊 **Sales Report** – Daily/Monthly sales reporting and summary.
  


## 🛠️ Technologies Used

- **Frontend**: VB.NET (Windows Forms Application)
- **Backend**: SQL Server
- **Database Connectivity**: ADO.NET



## 🖥️ How to Run

1. Clone the repository:

   
   git clone https://github.com/Shubhamraj1909/Cafe_Management_System.git
   

2. Open the solution (`.sln`) file in **Visual Studio**.

3. Configure your **SQL Server**:
   - Create a new database using the provided `.sql` file.
   - Update the **connection string** in your `App.config` or code.

4. Build and run the project.



## 🧩 Folder Structure


📁 CafeManagementSystem
├── 📂 Forms           # All Windows Forms (UI)
├── 📂 Database        # .sql file to set up database schema
├── 📂 Classes         # Business logic and data access
├── My Cafe.sln       # Visual Studio Solution




## 🗃️ Database

- The database includes the following tables:
  - `MenuItems`
  - `Orders`
  - `OrderDetails`
  - `Customers`
  - `Inventory`
  - `Users` (for login)
  - `Payments`
  - `Reports`


