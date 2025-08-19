# BookVault-Secure-Library-Management


[![Spring Boot](https://img.shields.io/badge/SpringBoot-3.2.0-brightgreen)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-blue)](https://react.dev/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen)]()

A **full-stack Library Management System** built with **Spring Boot**, **MongoDB**, **React**, and **TailwindCSS**.  
It supports **role-based access**, **JWT authentication**, **book reservations**, and an **admin dashboard** for efficient library management.  

---

## 🌐 Demo & Repository

🚀 [GitHub Repository](https://github.com/shishiro26/library-management-system)  
🔗 Deploy backend using **Render/Railway** and frontend using **Vercel/Netlify**.  

---

## 🛠️ Tech Stack

### Frontend
- React 18  
- React Router  
- TailwindCSS  
- Axios  
- JWT Authentication  
- Context API  

### Backend
- Java 21  
- Spring Boot 3.2.0  
- Spring Security  
- MongoDB  
- JWT (JSON Web Tokens)  
- CORS Configuration  
- Maven  

---

## ✨ Features

### 👨‍💼 User
- Signup/Login with JWT  
- Browse and search books  
- Filter by category  
- Reserve and return books  
- View reservation history  
- Manage profile  

### 🛡️ Admin
- Add/Edit/Delete books  
- Manage users and reservations  
- Admin-only dashboard  
- Monitor system usage  

---

## 📁 Project Structure

├── frontend/ 
│ └── src/
│ ├── pages/
│ ├── components/
│ ├── context/
│ └── App.js
├── backend/ 
│ └── src/main/java/com/library/
│ ├── controller/
│ ├── model/
│ ├── repository/
│ ├── service/
│ └── config/


---

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)  
- Java 21  
- MongoDB (local/cloud)  
- Maven 3.6+  

---

### 🔧 Backend Setup

cd backend
mvn clean install


###  
Start MongoDB at mongodb://localhost:27017

Copy config file:

cp src/main/resources/application.sample.properties src/main/resources/application.properties

Update application.properties (JWT secret, DB name, CORS origin)

Run backend:

mvn spring-boot:run


👉 Runs at: http://localhost:8080/api
