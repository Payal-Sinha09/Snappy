# Snappy Chat Application

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Screenshots](#project-screenshots)
- [Usage](#usage)
- [Contact](#contact)

## Overview
Snappy Chat Application is a real-time chat platform built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to send and receive messages instantly. The app supports multiple chat rooms and real-time messaging functionality using WebSockets.

## Features
- Real-time messaging with WebSocket (Socket.IO)
- User authentication (Login/Sign-up)
- Create and join multiple chat rooms
- Responsive user interface
- Backend API for managing chat data

## Technologies Used
- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.IO
- **Other**: JWT (for authentication), bcrypt (for password hashing)

## Setup Instructions

### Prerequisites
- Node.js installed on your system
- MongoDB installed locally or access to a cloud MongoDB database (e.g., MongoDB Atlas)

### Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/snappy-chat-app.git
   cd snappy-chat-app

2. **Backend Setup**
This section guides you through setting up the backend server for the Snappy Chat Application.  


- **Step 1**: Navigate to the Server Folder  
After cloning the repository, move into the server directory:  
```bash
cd server  
```

- **Step 2**: Install Required Dependencies  
Install the necessary Node.js packages using npm:
```bash
npm install
```

- **Step 3**: Configure Environment Variables  
Create a .env file in the server directory and add your configuration settings, including your MongoDB connection string and JWT secret.  
Here’s a sample of what to include:
```plaintext
MONGO_URI=your_mongo_connection_string  
JWT_SECRET=your_jwt_secret_key  
```

- **Step 4**: Start the Backend Server  
You can now start the backend server using the following command:   
```bash
npm start  
```
The backend server will run on http://localhost:5000 by default. Make sure your MongoDB server is running, or you're connected to a cloud MongoDB service.  

## Troubleshooting
Ensure that Node.js and MongoDB are installed and configured correctly.
Check the console for any error messages during the installation or startup process and resolve them accordingly.

# Project Screenshots
## 1. Login Screen
![Login Screen](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(156).png)

## 2. Signup Screen
![Signup Screen](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(159).png)

## 3. Avatar Setup
![Avatar Setup](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(160).png)

## 4. Chat Room Interface
![Chat Room](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(161).png)

## 5. Real-time Messaging
![Messaging](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(162).png)


# Usage
1. User Registration and Login:
Users can sign up with their email and password.
Passwords are securely hashed using bcrypt and stored in MongoDB.
2. Real-time Messaging:
Users can create and join chat rooms.
Messages are exchanged in real time using Socket.IO for seamless communication.
3. Message Persistence:
All chat history is stored in MongoDB, so users can view past conversations when they log back in.
4. Authentication:
JWT (JSON Web Tokens) is used to authenticate users, ensuring secure and protected messaging.
Future Enhancements
Direct Messaging: Implement one-on-one messaging between users.
Typing Indicators: Show when a user is typing in a chat room.
Message Encryption: Add end-to-end encryption for secure messaging.
Push Notifications: Implement real-time push notifications for new messages.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact
For any questions or feedback, feel free to contact me:
**Email:** payal09apr@gmail.com
**Portfolio:** [myportfoliopayal.netlify.app](https://myportfoliopayal.netlify.app/)
