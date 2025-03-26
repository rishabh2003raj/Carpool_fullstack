Carpool – Full-Stack Ride-Sharing Platform


A MERN stack (MongoDB, Express.js, React.js, Node.js) application connecting drivers and passengers with real-time ride matching, secure authentication, and interactive maps.

✨ Features
Real-Time Ride Matching

Interactive maps using Google Maps API.

Dynamic ride pairing based on location and availability.

User Authentication

JWT-based signup/login for drivers and passengers.

Protected routes for secure access.

Ride Management

Create, book, update, or cancel rides (full CRUD operations).

Ride history and status tracking.

Optimized Database

MongoDB schema with Mongoose ODM for fast queries.

Scalable design for user profiles and ride data.

🛠️ Tech Stack
Frontend	Backend	Database	APIs & Tools
React.js	Node.js	MongoDB	Google Maps API
Material-UI	Express.js	Mongoose ODM	JWT Authentication
Axios (HTTP client)	RESTful API		Postman (API testing)
🚀 Getting Started
Prerequisites
Node.js (v16+)

MongoDB Atlas (or local instance)

Google Maps API key

Installation
Clone the repository



bash
Copy
cd backend  
npm install  
cp .env.example .env  # Add your MongoDB URI, JWT secret, etc.  
npm start  
Set up frontend

bash
Copy
cd ../frontend  
npm install  
cp .env.example .env  # Add your Google Maps API key  
npm start  
Access the app

Frontend: http://localhost:3000

Backend: http://localhost:5000

