🚀 E-Commerce Project
Full-stack Web Application built with React (Frontend) & Spring Boot (Backend)
<p align="center"> <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react" /> <img src="https://img.shields.io/badge/Backend-SpringBoot-brightgreen?style=for-the-badge&logo=springboot" /> <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?style=for-the-badge&logo=postgresql" /> </p>
📘 Overview

This is a full-stack E-Commerce web application built with a modern architecture.
It includes complete product management, cart functionality, image upload, and a seamless connection between frontend and backend.

🌐 Live Preview (if you deploy later)

Add your deployed link here.

🧩 Project Features
🎨 Frontend – React (Vite)

Beautiful & responsive UI

Product listing with images

Add to cart functionality

Cart management

Product search bar

Smooth UX with modern components

Fully integrated with Spring Boot REST APIs

🔧 Backend – Spring Boot

Complete Product CRUD

Image upload stored in PostgreSQL

REST API for frontend

Order API (Add / View Orders)

CORS enabled for React

Secure & scalable architecture

🏗️ Tech Stack
🎯 Frontend
Technology	Purpose
React (Vite)	Frontend framework
Axios	API calls
Bootstrap / Custom CSS	Styling
JavaScript	Logic
⚙️ Backend
Technology	Purpose
Spring Boot	Backend Framework
Spring Web	REST APIs
Spring Data JPA	Database ORM
PostgreSQL	Database
Hibernate	ORM framework
📁 Project Structure
ecommerce-project/
   ├── Ecom-backend/      # Spring Boot backend
   └── Ecom-frontend/     # React + Vite frontend

🚀 How to Run the Project
▶️ 1. Start the Backend
cd Ecom-backend
mvn spring-boot:run

▶️ 2. Start the Frontend
cd Ecom-frontend
npm install
npm run dev

📡 API Endpoints
Method	Endpoint	Description
POST	/product	Add product
GET	/products	Get all products
GET	/product/{id}	Get product by ID
PUT	/product/{id}	Update product
DELETE	/product/{id}	Delete product
POST	/orders	Place order
GET	/orders	Get all orders
