# 🏥 Clinic Appointment Booking System

A modern full-stack web application that enables patients to book appointments online and helps clinics manage appointments efficiently.

---

## 🚀 Tech Stack

### Frontend

* React.js
* Vite
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Tokens)
* bcrypt

---

## ✨ Features

* Online Appointment Booking
* Doctor Listing & Profiles
* Appointment Management Dashboard
* Patient Contact Form
* Secure Admin Login
* Responsive and User-Friendly Interface

---

## 📂 Project Structure

```bash
clinic-booking-system/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.jsx
└── database/
```

---

## 📋 Main Modules

* Home Page
* About Clinic
* Doctors Section
* Book Appointment
* Contact Us
* Admin Dashboard

---

## 🔗 API Endpoints

### Authentication

```http
POST /api/auth/login
GET /api/auth/me
```

### Appointments

```http
POST /api/appointments
GET /api/appointments
PUT /api/appointments/:id
DELETE /api/appointments/:id
```

### Doctors

```http
GET /api/doctors
POST /api/doctors
```

---

## 🔒 Security Features

* JWT Authentication
* Password Encryption using bcrypt
* Protected Admin Routes
* Secure API Access

---

## 🛠 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/clinic-booking-system.git
cd clinic-booking-system
```

### Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### Start the Application

#### Backend

```bash
npm run server
```

#### Frontend

```bash
npm run dev
```

---

## 🔮 Future Enhancements

* Online Payment Integration
* SMS and Email Notifications
* Telemedicine Support
* Patient Medical Records
* Doctor Availability Scheduling

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Renuka Sanku**

Aspiring Full Stack Developer passionate about building scalable and user-friendly web applications.
