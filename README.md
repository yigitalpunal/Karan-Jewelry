# 💎 JewelryShop

**JewelryShop** is a modern e-commerce web application developed for showcasing and selling jewelry products. Built with **ASP.NET Core MVC**, it allows users to view product details, filter by category, search by keyword, sort by price or name, and add products to a shopping cart. The design is clean, responsive, and ready for future enhancements.

---

## 🌟 Features

- ✅ Dynamic product listing from a real SQL database
- ✅ Search, category filtering and sorting (by price or name)
- ✅ Fully functional shopping cart system
- ✅ Seed data integration – products are automatically inserted into the database if empty
- ✅ Responsive front-end UI with product images
- ✅ MVC architecture: Models, Views, Controllers
- ✅ Clean and modular codebase (ideal for expansion)

---

## 🧰 Technologies Used

- ASP.NET Core MVC (.NET 6 / 8 compatible)
- Entity Framework Core (Code First)
- SQL Server LocalDB
- Razor Views
- Bootstrap 5 / HTML / CSS
- LINQ filtering/sorting
- GitHub for version control

---

## ⚙️ How to Run the Project

1. )
**Clone or Download the Repository**
   ```bash
   git clone https://github.com/yigitalpunal/Karan-Jewelry

2.)
Open JewelryShop.sln in Visual Studio

3.)
Restore NuGet Packages (Visual Studio usually does this automatically)

4.)
Update the Database
Open the Package Manager Console and run:
Update-Database

5.)
Run the Application

Press F5 or click "Start"

Navigate to: https://localhost:{port}/Product

---

## 🌱 Seed Data
If the Products table is empty, the application will automatically populate it with 9 sample jewelry products on first run using the SeedData.Initialize() method.

---

## 📌 Project Status
✅ This project includes:

- Product display, search, filter, sort
- Shopping cart functionality
- Working database with seed data
- Clean user interface

---

## 🛠️ Coming Soon:

- Admin panel (CRUD for products)
- User authentication (login/register)
- Role-based authorization (admin vs. customer)
- Order history, checkout system

---

## 🧑‍💻 Author
Yiğit Alp ÜNAL
📧 unalyigitalpp@gmail.com
🔗 GitHub: @yigitalpunal

---

## 📄 License
This project is licensed under the MIT License. You are free to use, modify, and share this code with attribution.
