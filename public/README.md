Snappy Chat Application
Table of Contents
Overview
Features
Technologies Used
Setup Instructions
Project Screenshots
Usage
Future Enhancements
License
Contact
Overview
Snappy Chat Application is a real-time chat platform built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to send and receive messages instantly. The app supports multiple chat rooms and real-time messaging functionality using WebSockets.

Features
Real-time messaging with WebSocket (Socket.IO)
User authentication (Login/Sign-up)
Create and join multiple chat rooms
Responsive user interface
Backend API for managing chat data
Technologies Used
Frontend: React, CSS
Backend: Node.js, Express.js
Database: MongoDB
Real-time Communication: Socket.IO
Other: JWT (for authentication), bcrypt (for password hashing)
Setup Instructions
Prerequisites
Node.js installed on your system
MongoDB installed locally or access to a cloud MongoDB database (e.g., MongoDB Atlas)
Steps to Run the Project
Clone the Repository:

bash
Copy code
git clone https://github.com/YourUsername/snappy-chat-app.git
cd snappy-chat-app
Backend Setup:

Navigate to the server folder:
bash
Copy code
cd server
Install the required dependencies:
bash
Copy code
npm install
Create a .env file and add your MongoDB connection string, JWT secret, and any other environment variables required:
env
Copy code
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key
Start the backend server:
bash
Copy code
npm start
Frontend Setup:

Navigate to the client folder:
bash
Copy code
cd client
Install the frontend dependencies:
bash
Copy code
npm install
Start the React app:
bash
Copy code
npm start
Access the App:

The app should be running at http://localhost:3000 for the frontend and http://localhost:5000 for the backend.
Project Screenshots
1. Login Page
## Login Screen
![Login Screen](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(156).png)

2. Signup Page
## Signup Screen
![Signup Screen](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(159).png)


3. Set Avatar
## Avatar Setup
![Avatar Setup](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(160).png)


4. Chat Room Interface
## Chat Room
![Chat Room](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(161).png)


5. Real-time Messaging
## Messaging
![Messaging](https://github.com/Payal-Sinha09/Snappy/blob/master/images/Screenshot%20(162).png)


Usage
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

Contact
For any questions or feedback, feel free to contact me:

Email: payal@example.com
Portfolio: myportfoliopayal.netlify.app