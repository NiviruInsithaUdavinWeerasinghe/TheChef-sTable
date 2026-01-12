# 👨‍🍳 The Chef's Table

**A comprehensive Restaurant Management System built with Java Swing.**

> **The Chef's Table** is a robust desktop application designed to digitize restaurant operations. It seamlessly connects the front-of-house (Cashiers) with the back-of-house (Chefs) while providing powerful oversight tools for Administration.

---

## 📸 Application Showcase

### 🛡️ Admin Dashboard & Analytics
Control center for business operations, staff management, and financial insights.

| **Management Modules** | **Analytics & Reporting** |
|:---:|:---:|
| <img width="100%" alt="Admin Staff Management" src="https://github.com/user-attachments/assets/a5ff7c3c-9fa6-40ba-be5f-745932102f93" /><br/><br/><img width="100%" alt="Admin Menu Management" src="https://github.com/user-attachments/assets/15a3cdb6-23db-4ef6-96cd-33cc24b24d31" /> | <img width="100%" alt="Monthly Sales Graph" src="https://github.com/user-attachments/assets/7eb12365-e1ad-4126-a46a-30134b24fdc0" /><br/><br/><img width="100%" alt="Jasper Sales Report" src="https://github.com/user-attachments/assets/be38002b-6d81-4abb-8853-12ba385c37d3" /> |
| *Manage Staff & Menus* | *Visual Graphs & PDF Reports* |

---

### 💵 Cashier Interface
Efficient order processing for front-line staff.

| **Order Placement (POS)** | **Transaction History** |
|:---:|:---:|
| <img width="100%" alt="Cashier Order Placement" src="https://github.com/user-attachments/assets/c7fb7e00-7af4-41fe-a14d-e63fac61bbff" /> | <img width="100%" alt="Cashier Order History" src="https://github.com/user-attachments/assets/6e98de7b-6013-4e12-9282-c0d8836ac119" /> |
| *Add items to cart & place orders* | *Review past transactions* |

---

### 🍳 Chef's Kitchen Display
Real-time order tracking for the kitchen staff.

| **Kitchen Workflow** |
|:---:|
| <img width="100%" alt="Chef Pending and Completed Orders" src="https://github.com/user-attachments/assets/7c18619e-a404-4985-a40f-dba60aeabe5d" /> |
| *View pending orders, mark as done, and see completion logs* |

---

### 💬 Global Communication System
A centralized chat hub accessible by **Admin**, **Cashiers**, and **Chefs**.

| **Team Chat** |
|:---:|
| <img width="100%" alt="Color Coded Chat System" src="https://github.com/user-attachments/assets/d0064b1a-557d-4130-b6f9-b1bddacf3614" /> |
| *Color-coded messages: **Red** (Admin), **Green** (You), **Gray** (Others)* |

---

## 🚀 Key Features

### 👤 Admin Module
* **Employee Management:** Add, update, or remove staff access (Cashiers/Chefs).
* **Menu Management:** Create and update menu items, prices, and categories.
* **Visual Analytics:** View interactive **Monthly Sales Graphs** generated via *JFreeChart*.
* **Automated Reporting:** Generate and export detailed **Monthly Sales Reports** using *JasperReports*.

### 🛒 Cashier Module
* **Point of Sale (POS):** Browse the digital menu, add items to a cart, and process payments.
* **Order Workflow:** Instantly send placed orders to the Chef's display.
* **Transaction History:** View a log of all processed orders and their status.

### 🍽️ Chef Module
* **Real-time Queue:** View pending orders immediately as they are placed by cashiers.
* **Order Status:** Mark orders as "Completed" to update the system and clear the queue.
* **Production Log:** Access a history of all prepared food items.

### 💬 Internal Chat System
A centralized communication hub connecting all staff members.
* **Admin Messages:** Highlighted in <span style="color:red">**Red**</span> for urgent notices.
* **Your Messages:** Displayed in <span style="color:green">**Green**</span> for easy identification.
* **Colleague Messages:** Displayed in **Gray**.

---

## 🛠 Tech Stack

* **Language:** Java (JDK 8+)
* **GUI Framework:** Java Swing (AWT)
* **Database:** MySQL
* **Reporting:** JasperReports
* **Charting:** JFreeChart
* **Architecture:** MVC (Model-View-Controller) Pattern

---

## 📂 Project Structure

The application follows a strict MVC architecture for maintainability:

* `src.ead1.repeat.View` - UI Forms (`AdminUI`, `CashierUI`, `ChefUI`, `LoginUI`).
* `src.ead1.repeat.Controller` - Logic handling user interactions (`SalesController`, `MessageController`).
* `src.ead1.repeat.Model` - Data Access Objects (DAOs) and Entities (`SalesDAO`, `OrderModel`).
* `src.ead1.repeat.Resources` - Icons, images, and JasperReport templates.
