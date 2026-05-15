# 🍽️ QR Restaurant Ordering System

A full-stack QR-based Restaurant Ordering & Management System built with Laravel, featuring customer ordering, admin dashboard, kitchen management, waiter assistance, payment integration, and real-time order tracking.

---

# 🚀 Project Highlights

- QR-Based Table Ordering
- Real-Time Order Tracking
- Admin Dashboard
- Kitchen Dashboard
- Waiter Assistance System
- Online Payment Integration
- Dynamic Menu Management
- Responsive Modern UI

---

# 🖼️ Project Screenshots

## 🏠 Customer Home Page

<p align="center">
  <img src="screenshots/Home%20Page.png" width="800"/>
</p>

---

## 🛒 Order Page

<p align="center">
  <img src="screenshots/Order%20Page.png" width="800"/>
</p>

---

## 💳 Checkout Pages

<p align="center">
  <img src="screenshots/Checkout%20Page.png" width="800"/>
  <img src="screenshots/Checkout%20Page%202.png" width="800"/>
</p>

---

## 📦 Active Order Tracking

<p align="center">
  <img src="screenshots/Active%20Order.png" width="800"/>
</p>

---

## 💰 Payment Page

<p align="center">
  <img src="screenshots/Payment%20Page.png" width="800"/>
</p>

---

## 📜 Order History

<p align="center">
  <img src="screenshots/Order%20History.png" width="800"/>
</p>

---

## 📢 Waiter Assistance Feature

<p align="center">
  <img src="screenshots/Waiter%20Call.png" width="800"/>
</p>

---

# 🧑‍💼 Admin Dashboard

## 📊 Dashboard Overview

<p align="center">
  <img src="screenshots/Dashboard%20Page.png" width="800"/>
</p>

---

## 🍔 Menu Management

<p align="center">
  <img src="screenshots/Dashboard%20Menu%20Page.png" width="800"/>
</p>

---

## 🪑 Table Management

<p align="center">
  <img src="screenshots/Dashboard%20Table.png" width="800"/>
</p>

---

# 🔎 Project Overview

This repository contains a QR-based restaurant ordering application designed for dine-in restaurants where customers can scan QR codes placed on tables and place orders directly from their mobile devices.

The platform streamlines restaurant operations by integrating customer ordering, kitchen management, waiter assistance, payment handling, and admin management into one centralized system.

---

# ✨ Key Features

- QR Code Table Ordering
- Dynamic Menu Categories
- Add to Cart & Checkout
- Real-Time Order Tracking
- Kitchen Order Management
- Waiter Assistance Requests
- Online Payment Integration
- Invoice & Billing System
- Admin Dashboard
- Table & QR Management
- Responsive Mobile-Friendly UI

---

# 🛠️ Technology Stack

## Backend
- Laravel
- PHP
- REST APIs

## Frontend
- Blade Templates
- Tailwind CSS
- JavaScript
- Vite

## Database
- MySQL / MariaDB

## Authentication
- Laravel Sanctum

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/Sujeetatwe/qr-restaurant-ordering-system.git
cd qr-restaurant-ordering-system
```

---

## Install Dependencies

```bash
composer install
npm install
```

---

## Configure Environment

```bash
cp .env.example .env
```

Update database credentials inside `.env`

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=restaurant_db
DB_USERNAME=root
DB_PASSWORD=
```

---

## Generate Application Key

```bash
php artisan key:generate
```

---

## Run Migrations & Seeders

```bash
php artisan migrate --seed
```

---

## Build Frontend Assets

```bash
npm run build
```

---

## Start Development Server

```bash
php artisan serve
```

---

# 🌐 Application Access

```text
http://127.0.0.1:8000
```

---

# 📊 Core Modules

- Customer Ordering Module
- Kitchen Dashboard
- Waiter Dashboard
- Admin Dashboard
- QR Table Management
- Menu Management
- Payment System
- Service Request System

---

# 🔐 System Features

- Role-Based Access
- Real-Time Order Status
- Dynamic QR Generation
- Mobile Responsive UI
- Secure Payment Handling
- Order History Tracking

---

# 📁 Project Structure

```text
app/                 → Laravel Controllers & Models
resources/views/     → Blade Templates
routes/              → Web & API Routes
database/            → Migrations & Seeders
public/              → Public Assets
storage/             → Uploaded Files
```

---

# 🧪 Testing

Run Laravel tests:

```bash
php artisan test
```

---

# 🚀 Deployment Notes

- Configure production `.env`
- Run:

```bash
php artisan config:cache
php artisan route:cache
npm run build
```

- Ensure proper permissions:

```text
storage/
bootstrap/cache/
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Sujeet Atwe

Full Stack & AI Developer focused on scalable web applications, enterprise systems, and modern business platforms.

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub.
