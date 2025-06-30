# Exclusive E-commerce Application

[![Demo Video](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://youtu.be/9xcSwET5D9w)

> **Watch the Exclusive Demo:** [YouTube Video](https://youtu.be/9xcSwET5D9w)  
> Click the image above or the link to watch a walkthrough of the Exclusive E-commerce Application.

> **Showcase Project — Not for Public Use or Contributions**  
> This repository is for demonstration purposes only. It showcases full-stack development using Laravel, React, Inertia.js,Tailwind CSS, and MySQL.

---

## 🏗️ Project Overview

**Exclusive** is a modern full-stack e-commerce platform designed to offer a smooth shopping experience for users and an intuitive admin interface for managing products, orders, and customers. Built with Laravel, React, Inertia.js, and Tailwind CSS, the application handles everything from catalog browsing to checkout and order administration.

---

## 🎯 Why Exclusive? (Skills Demonstrated)

- **Full-Stack Architecture:** Laravel backend with a dynamic React frontend bridged via Inertia.js  
- **Authentication System:** Secure user authentication and password reset, with social login via Google  
- **Role-Based Access:** Customer and admin dashboards with protected routing  
- **Responsive Design:** Tailored user experience across devices using Tailwind CSS  
- **State Management & UX:** Persistent cart and wishlist, toast feedback, and fast SPA behavior  
- **Admin Tools:** Dashboard insights, product management, and order handling with data visualization

---

## ✨ Key Features

### 🛍️ Customer Experience

- **Browse Products:** Explore product categories, subcategories, and search dynamically  
- **Product Pages:** View detailed descriptions, related items, and customer reviews  
- **Shopping Cart:** Add/remove/update items — supports guests and authenticated users  
- **Wishlist:** Save favorites for later access  
- **Order History:** View past orders, statuses, and detailed items  
- **Authentication:** Register/login with email or Google OAuth  
- **Flash Sales:** Limited-time offers with countdowns  
- **Contact Form:** Reach out directly from the platform

### 🛠️ Admin Panel

- **Dashboard Overview:** Total orders, revenue, users, and daily statistics  
- **Order Management:** View, update, and manage all user orders  
- **Product Management:** Full CRUD operations with media uploads  
- **Category Management:** Add, edit, and organize categories and subcategories  
- **User Management:** View and manage customer accounts

---

## 🔧 Technical Highlights

- **Backend:** Laravel 12 (PHP 8.2), Eloquent ORM, Laravel Breeze for authentication scaffolding  
- **Authentication & Authorization:** Laravel Sanctum (SPA tokens), Laravel Socialite (OAuth), role-based access  
- **SPA Architecture:** Inertia.js (Laravel adapter + `@inertiajs/react`) for seamless backend-frontend bridging  
- **Frontend:** React 19, Tailwind CSS for responsive and utility-first styling  
- **State Management:** React `useContext` for managing cart and wishlist states  
- **Payments:** Stripe integration using Laravel Cashier for handling secure transactions  
- **Media Hosting & Optimization:** Cloudinary (`@cloudinary/react`, `@cloudinary/url-gen`, and Laravel SDK)  
- **Data Visualization:** Chart.js + React-Chartjs-2 for admin analytics and dashboard metrics  
- **Notifications:** `react-hot-toast` for real-time feedback and alerts  
- **Routing:** Ziggy for sharing Laravel routes with React components  
- **Database Tools:** Doctrine DBAL for advanced migrations (e.g., renaming columns)  
- **Asynchronous Processing:** Laravel queues for handling emails and background jobs  
- **Dev Tools:** Laravel Tinker for REPL-style backend testing and debugging  
- **Icons:** `lucide-react` for scalable and consistent iconography  


---

## ⚙️ How the Project Works

### Customer Flow

1. Browse the homepage, explore flash sales,best sellers products, categories, or search
2. View product details and add to cart or wishlist or buy it directly
3. Register/login using email or Google
4. Proceed to checkout and place an order
5. Review past orders and edit/remove review
6. Send feedback or inquiries via the contact form
7. Add/remove Items to wishlist
8. Add/remove Items to cart
9. Enter/Edit billing info for future purchases 
    

### Admin Flow

1. Access admin panel via secure route
2. View dashboard stats and recent orders and top selling products
3. Manage products, orders, categories, and users
4. Track daily performance using dynamic charts

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](./screenshots/homepage.png)

### 📦 Product Page
![Product Page](./screenshots/product.png)

### 🛒 Cart Drawer
![Cart Drawer](./screenshots/cart.png)

### 🔐 Login Page
![Login Page](./screenshots/login.png)

### 📊 Admin Dashboard
![Admin Dashboard](./screenshots/admin-dashboard.png)

### 🗂️ Product Management
![Product Management](./screenshots/admin-products.png)

### 📑 Orders Management
![Orders Management](./screenshots/admin-orders.png)

---

## 📬 Contact

For questions or to discuss the project:

- GitHub: [yourusername](https://github.com/yourusername)  
- Email: your.email@example.com  
- Portfolio: [yourportfolio.com](https://yourportfolio.com)

---

© 2025 Exclusive. All rights reserved.
