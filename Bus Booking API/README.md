# 🚌 Bus Booking System API  

## 📌 Overview  
This project is a **Bus Booking System API** built using **Express.js** and **MongoDB**. It supports **JWT-based authentication** with refresh tokens and provides **admin and user functionalities** for managing buses, routes, bookings, and cancellations.  

## 🛠️ Tech Stack  
- **Backend Framework:** Express.js  
- **Database:** MongoDB (Mongoose ODM)  
- **Authentication:** JWT with refresh token functionality  
- **Containerization:** Docker  

## ✨ Features  

### 👨‍💼 Admin Role  
- **Bus Management:** Add and update bus details.  
- **Route Management:** Add and update routes.  

### 👤 User Role  
- **Bus Search:** Search and view available buses.  
- **Booking & Cancellation:** Book a bus and cancel bookings.  

### 🔐 Security  
- **JWT-based authentication and authorization.**  
- **Refresh token functionality for seamless authentication.**  

### 🚀 Deployment  
- **Docker containerization** for a consistent deployment environment.  

## 📂 API Documentation  
Comprehensive API documentation is available via **Postman Collection**.  

- [Postman Collection](https://documenter.getpostman.com/view/42576066/2sAYdfrBmJ)   
- API routes and usage are detailed in the documentation.  

## 🏗️ Getting Started  

### 🔧 Prerequisites  
Ensure you have the following installed:  
- Node.js  
- MongoDB  
- Docker (optional for containerization)  

### 🛠 Installation  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/bus-booking-api.git
   cd bus-booking-api
   ```

2. **Install Dependencies**  
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**  
   Create a `.env` file and add the required configuration:  
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   JWT_REFRESH_SECRET=your_refresh_secret_key
   ```

4. **Start the Server**  
   ```bash
   npm start
   ```

5. **Run with Docker** (Optional)  
   ```bash
   docker build -t bus-booking-api .
   docker run -p 5000:5000 bus-booking-api
   ```

## 📌 API Endpoints  

### 🔐 Authentication  
- **`POST /api/auth/register`** – Register a new user.  
- **`POST /api/auth/login`** – Log in and get access/refresh tokens.  
- **`POST /api/auth/refresh-token`** – Get a new access token using the refresh token.  

### 🚌 Bus Management (Admin Only)  
- **`POST /api/buses`** – Add a new bus.  
- **`PUT /api/buses/:id`** – Update bus details.  

### 📍 Route Management (Admin Only)  
- **`POST /api/routes`** – Add a new route.  
- **`PUT /api/routes/:id`** – Update route details.  

### 🔍 User Functionalities  
- **`GET /api/buses/search`** – Search for available buses.  
- **`POST /api/bookings`** – Book a bus.  
- **`DELETE /api/bookings/:id`** – Cancel a booking.
