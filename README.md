# Drivezy

Drivezy is a full-stack Car Rental Platform with **User**, **Admin**, and **Vendor** modules. Built with modern web technologies, it enables seamless vehicle booking, listing, and management with secure role-based access and smart automation features.

---

## Features & Implementations

### 🔐 Authentication & Access Control
- JWT-based authentication using access and refresh tokens.
- Role-based access for User, Admin, and Vendor.
- Google OAuth integration for quick sign-up/sign-in.

### 👤 User Module
- Browse, filter, and book available vehicles.
- View and manage bookings and profile.
- Receive email confirmations for bookings.

### 🧑‍💼 Admin Module
- Manage users, vehicles, bookings, and vendors.
- Approve/reject vendor applications.
- Monitor platform activity.

### 🚗 Vendor Module
- Vendor registration and login flow.
- List vehicles for admin approval.
- Manage orders and receive notifications.

### 📦 Core Features
- Razorpay payment integration.
- Dynamic location-based vehicle search.
- Image/video uploads using Multer + Cloudinary.
- Strong form validation using Zod + React Hook Form.
- Redux Toolkit for state management.
- Clean and responsive UI built with TailwindCSS and Material UI.

---

## Tech Stack

**Frontend:** React.js (Vite), Redux Toolkit, Tailwind CSS, Material UI, React Toast, React Hook Form, Zod  
**Backend:** Node.js, Express.js, MongoDB, Multer, Nodemailer, Cloudinary  
**Deployment:** Frontend on **Vercel**, Backend on **Render**

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/TanayDhokariya/Drivezy.git


### 2.Install Backend
cd backend
npm install
npm run dev



### 3.Install Frontend
cd client
npm install
npm run dev




