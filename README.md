# 🏢 ERP Management System

### Full Stack Enterprise Resource Planning Application

Built with **Spring Boot + Angular**

---

## 📌 Overview

The **ERP Management System** is a full-stack enterprise application designed to manage core business operations such as **products, customers, suppliers, sales orders, purchase orders, inventory (GRN), invoices, and reports**.

The system provides a **secure, role-based web interface** with real-time data handling through **REST APIs built using Spring Boot** and a dynamic frontend built with **Angular**.

This project demonstrates practical implementation of **enterprise software architecture, secure authentication, modular backend services, and responsive frontend design**.

---

## 🚀 Tech Stack

### Backend

* Java 17
* Spring Boot
* Spring Security
* JWT Authentication
* Spring Data JPA (Hibernate)
* MySQL Database
* Swagger (API Documentation)
* Maven

### Frontend

* Angular 17
* RxJS
* Angular Forms
* Angular Routing
* Chart.js (Dashboard charts)
* TypeScript
* HTML + CSS

---

## 🧩 System Modules

### 📦 Product Management

* Add / Update / Delete products
* View product inventory
* Stock level monitoring

### 👥 Customer & Supplier Management

* Manage customer records
* Manage supplier information
* CRUD operations with database integration

### 🧾 Sales Order Management

* Create and manage sales orders
* Add products with quantity
* Automatic total calculation

### 🏭 Purchase Order Management

* Create purchase orders
* Track purchase status

### 📥 GRN (Goods Receipt Note)

* Record received goods from suppliers
* Automatic inventory stock update

### 🧾 Invoice Management

* Generate invoices from sales orders
* View invoice history
* Download invoice as PDF

### 📊 Dashboard & Reports

* Total products
* Total customers
* Total sales
* Total purchases
* Sales trend chart
* Purchase trend chart
* Low stock monitoring

### 🔐 Authentication & Security

* JWT Authentication
* Role-based access control
* Angular Route Guards
* Secure API endpoints

---

## 🏗 Project Architecture

```
Angular Frontend
        │
        │ HTTP Requests
        ▼
Spring Boot REST API
        │
        │
Spring Security + JWT
        │
        ▼
MySQL Database
```

---

## 📂 Project Structure

```
ERP-System
│
├── backend
│   ├── controllers
│   ├── services
│   ├── repositories
│   ├── models
│   ├── security
│   └── application.properties
│
├── frontend
│   ├── pages
│   │   ├── login
│   │   ├── dashboard
│   │   ├── products
│   │   ├── customers
│   │   ├── suppliers
│   │   ├── sales-orders
│   │   ├── purchase-orders
│   │   ├── grn
│   │   ├── invoices
│   │   └── reports
│   │
│   ├── services
│   └── guards
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/erp-management-system.git
```

---

### 2️⃣ Backend Setup

```
cd backend
mvn spring-boot:run
```

Backend will start at:

```
http://localhost:8080
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
ng serve
```

Frontend will run at:

```
http://localhost:4200
```

---

## 📘 API Documentation

Swagger API documentation is available at:

```
http://localhost:8080/swagger-ui.html
```

---

## 📊 Key Features

✔ Full Stack Enterprise Application
✔ RESTful API Architecture
✔ Secure Authentication with JWT
✔ Modular ERP Design
✔ Dashboard Analytics
✔ Invoice Generation
✔ Inventory Tracking
✔ Role-Based Access Control

---

## 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

* Full Stack Web Development
* REST API Design
* Spring Boot Enterprise Architecture
* Angular Application Development
* Secure Authentication (JWT)
* Database Design & Integration
* Frontend-Backend Integration

---

## 👨‍💻 Author

**Arnav Kumar**
Master of Computer Applications (MCA)

---

⭐ If you found this project helpful, feel free to give it a **star on GitHub**.
