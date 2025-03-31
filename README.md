# 🎯 Live Polling System - Backend   [Live](https://live-polling-system-backend-0w3p.onrender.com)

The **Live Polling System** backend powers real-time interactions, user authentication, and poll management. Built with **Node.js**, **Express.js**, and **Socket.IO**, it ensures seamless communication between clients and the server.

## 🚀 Features

✅ **User Authentication** – Secure login for teachers and session handling.\
✅ **Poll Management** – Create, update, and delete polls.\
✅ **Real-Time Voting** – WebSocket-based live vote updates.\
✅ **Chat System** – Enables live discussions.\
✅ **Participant Control** – Teachers can manage and remove users.\
✅ **Scalable API** – RESTful API endpoints for frontend interaction.

## 🛠️ Tech Stack

🔹 **Node.js & Express.js** – Backend server and API handling.\
🔹 **Socket.IO** – Real-time bidirectional communication.\
🔹 **MongoDB** – Database for storing polls and user data.\
🔹 **JWT** – Authentication and session management.

## ⚡ Quick Start

### 📌 Prerequisites

Ensure you have **Node.js v14+**, **MongoDB**, and **npm/yarn** installed.

### 🏗 Installation

```bash
git clone https://github.com/your-repo/live-polling-system.git  
cd live-polling-system/backend  
npm install  
```

### 🔑 Setup Environment

Create a `.env` file in the `backend` folder and add:

```
PORT=5000  
MONGO_URI=mongodb://localhost:27017/livepolls  
JWT_SECRET=your_secret_key  
CLIENT_URL=http://localhost:5174  
```

### ▶️ Run the Server

```bash
npm run dev  
```

The server will start at **http\://localhost:3000**.

## 📂 **Project Structure**

📁 **src/controllers/**  
   📌 Handles request logic (authentication, polls, voting).  

📁 **src/models/**  
   📌 Mongoose schemas for MongoDB collections (Poll, User).  

📁 **src/routes/**  
   📌 Defines API endpoints (loginRoutes, pollRoutes, chatRoutes).  

📁 **src/config/**  
   📌 Contains database connection and environment configuration.  

📁 **src/utils/**  
   📌 Utility functions (error handling, JWT authentication, helpers).  

📄 **src/app.js**  
   📌 Initializes Express and middleware.  

📄 **src/socket.js**  
   📌 Handles WebSocket communication for real-time updates.  

📄 **server.js**  
   📌 Main entry point for running the backend server.  

## 🚀 Deployment

1️⃣ Build and start the production server:

```bash
npm run build  
npm start  
```

2️⃣ Deploy using **Heroku, AWS, Render, or any cloud platform**.

## 🤝 Contributing

Got ideas or improvements? Fork the repo, make changes, and submit a PR!

## 📜 License

Licensed under the **MIT License**. See the [LICENSE](../LICENSE) file for details.

## 📧 Contact

For inquiries, reach out at **[sahrohitkumar10@gmail.com](mailto\:sahrohitkumar10@gmail.com)**.

🔹 Happy Coding! 🚀

