# 🚀 Full-Stack Projects Repository  

This repository contains two full-stack projects:  

1. **🚌 Bus Booking System API** - A backend API for managing bus bookings, routes, and user authentication.  
2. **🚗 Second-hand Car Buying Application** - A web-based platform for buying and selling second-hand cars.  

Each project is contained in its own folder with separate documentation.  

---

## 📂 Project Structure  

```bash
.
├── bus-booking-api/           # Backend for bus booking system (Express + MongoDB)
│   ├── src/                   # API source code
│   ├── package.json           # Project dependencies
│   ├── README.md              # Detailed documentation for Bus Booking API
│   └── ...                    # Other backend-related files
│
├── second-hand-car-app/       # Frontend for second-hand car platform (React + Firebase/Supabase)
│   ├── src/                   # Frontend source code
│   ├── package.json           # Project dependencies
│   ├── README.md              # Detailed documentation for Car Buying App
│   └── ...                    # Other frontend-related files
│
├── README.md                  # This general repository documentation
```

---

## 🛠️ Tech Stack  

| Feature               | Bus Booking System API       | Second-hand Car App      |
|----------------------|-------------------------|----------------------|
| **Frontend**        | -                         | React  |
| **Backend**         | Express.js (Node.js)      | No backend required   |
| **Database**        | MongoDB                   | Firebase / Supabase  |
| **Authentication**  | JWT + Refresh Tokens      | Google Auth          |
| **Deployment**      | Docker                    | Responsive Web App   |

---

## 📜 Project Descriptions  

### 🚌 Bus Booking System API  
A backend API built with **Express.js** and **MongoDB** that provides authentication, bus management, route management, and user booking functionality.  

📌 **Features:**  
✔ JWT authentication with refresh tokens  
✔ Bus & route management (Admin)  
✔ Bus search & booking (Users)  
✔ Dockerized for deployment  

📖 [Detailed Documentation](https://documenter.getpostman.com/view/42576066/2sAYdfrBmJ)  

---

### 🚗 Second-hand Car Buying Application  
A React-based frontend application that allows users to search, list, and request to purchase second-hand cars. Authentication is handled via **Google Auth**, and data is stored in **Firebase/Supabase**.  

📌 **Features:**  
✔ Google authentication  
✔ Car listing and price updates (Admin)  
✔ Car search and purchase requests (Users)  
✔ Fully responsive web design   

---

## 🏗️ Getting Started  

### 🔧 Prerequisites  
- Install **Node.js** and **MongoDB** for the backend.  
- Set up **Firebase or Supabase** for the frontend.  
- Install **Docker** (optional for backend deployment).  

### 🛠 Installation  

#### 1️⃣ **Bus Booking System API**  
```bash
cd bus-booking-api
npm install
npm start
```

#### 2️⃣ **Second-hand Car App**  
```bash
cd second-hand-car-app
npm install
npm start
```

