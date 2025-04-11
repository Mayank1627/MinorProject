# Inventory Management Dashboard

An interactive web-based **Inventory Management System** that allows admins to manage suppliers, stores, orders, and track real-time business metrics like **sales**, **purchases**, **profit**, and more. The dashboard also includes dynamically generated visualizations using **Chart.js** and integrates with a **MySQL** database.

---

## 🔧 Features

- 📦 **Inventory Management**: Track product quantities, orders, and suppliers.
- 📊 **Dashboard Analytics**:
  - Sales, Purchases, Profit, and Cost overview.
  - Quantity in hand, purchase amount, revenue, and pending stock.
- 🧮 **Real-Time Charts**:
  - Sales & Purchase bar graph.
  - Line charts for order trends.
- 👨‍💼 **Supplier & Store Management**:
  - Add/edit/delete suppliers and store locations.
- 📝 **Order Tracking**:
  - Capture product details, quantity, order value, selling price, and category.
  - Auto-record order date.
- 💾 **Persistent Storage**: Powered by MySQL, integrated via PHP.

---

## 📁 Folder Structure

MinorProject/ ├── Pages/ │ ├── Orders.html │ ├── Suppliers.html │ ├── Store.html │ └── ... ├── CSS/ │ ├── index.css │ └── output.css ├── IMG/ │ └── (Icons, Logos, Product Images) ├── php/ │ ├── connection.php │ ├── add_order.php │ ├── fetch_orders.php │ ├── add_supplier.php │ ├── fetch_suppliers.php │ ├── add_store.php │ ├── fetch_stores.php │ ├── fetch_dashboard_stats.php │ ├── fetch_sales_purchase_data.php │ └── ... ├── Components/ │ └── Searchbar.html ├── index.php └── README.md


---

## 📦 Database Schema

**Tables Used:**

- `orders` – stores all order-related data
- `suppliers` – supplier details
- `stores` – individual store locations
- `products` – product list (optional, if linked)

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Tailwind), JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Visualization**: Chart.js

---

## 👥 Authors

- **Satyam**
- **Sumit**
- **Nikhil**
- **Mayank**

---

## 🧠 Future Enhancements

- Email notifications for low stock
- Role-based authentication (admin/user)
- Export reports to PDF/CSV
- REST API endpoints for external integrations

---

## ⚙️ Setup Instructions

1. Import the SQL tables to your MySQL server.
2. Update `/php/connection.php` with your DB credentials.
3. Run the project using a local server (e.g., XAMPP).
4. Access the dashboard via `http://localhost/MinorProject/index.php`

---

> 🔐 This project is intended for learning and demonstration purposes.
