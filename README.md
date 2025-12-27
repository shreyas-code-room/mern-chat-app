💬 MERN Chat Application
📌 Project Overview

This is a full-stack MERN Chat Application that allows users to register, authenticate, and chat in real time.
The project is built with a separate frontend and backend architecture, following industry-standard MERN practices.

It focuses on:

Secure authentication

Real-time communication

Clean REST API design

Scalable folder structure

🎯 Core Features (As Implemented)

User registration & login using JWT authentication

Secure password handling

One-to-one real-time chat

Messages stored in MongoDB

Real-time message delivery using Socket.io

Responsive React UI

Backend API separation from frontend

🛠️ Technology Stack
Frontend (React)

React.js

JavaScript (ES6+)

Axios (API communication)

React Hooks

CSS for styling

Backend (Node.js)

Node.js

Express.js

MongoDB & Mongoose

JSON Web Tokens (JWT)

Socket.io (real-time messaging)

Tools

Git & GitHub

MongoDB Atlas

Postman

VS Code

📂 Folder Structure
mern-chat-app/
│
├── backend/
│   ├── controllers/        # Business logic
│   ├── models/             # Mongoose schemas
│   ├── routes/             # API routes
│   ├── middleware/         # Auth & error handling
│   ├── server.js           # Backend entry point
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/     # UI components
│   │   ├── pages/          # App pages
│   │   ├── context/        # State management
│   │   └── App.js
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md

🚀 Running the Project Locally
✅ Prerequisites

Node.js (v16+)

MongoDB (Local or MongoDB Atlas)

npm

1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/mern-chat-app.git
cd mern-chat-app

2️⃣ Backend Setup
cd backend
npm install


Create a .env file inside backend/:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Start backend:

npm run dev


Backend runs on:

http://localhost:5000

3️⃣ Frontend Setup

Open a new terminal:

cd frontend
npm install
npm start


Frontend runs on:

http://localhost:3000

🔐 Authentication Flow (Implemented)

User registers or logs in

Backend generates a JWT token

Token is used to access protected routes

Messages are sent and received via Socket.io

Chat data is stored securely in MongoDB

🧪 Testing & Validation

API endpoints tested using Postman

Manual UI testing for chat flow

Authentication & token validation tested across routes

📈 Planned Enhancements

Group chat support

Message read receipts

Typing indicators

Media/file sharing

Deployment on Vercel (frontend) & Render (backend)

⭐ Project Highlights

Real-time MERN stack implementation

Clean separation of frontend & backend

Secure authentication using JWT

Industry-standard project structure

Strong project for MERN / Full-Stack Developer roles

🔥 Optional Improvements (Resume Boost)

Add screenshots to README

Deploy live demo

Add API documentation

Pin repository on GitHub profile
