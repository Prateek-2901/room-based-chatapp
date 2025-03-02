Overview
A real-time chat application that enables users to create and join chat rooms for seamless communication. The app leverages WebSockets for instant messaging and MongoDB for efficient data storage.

Features
✅ Real-time messaging with WebSockets
✅ Create and join chat rooms dynamically
✅ User authentication & session management
✅ Message history persistence using MongoDB
✅ Scalable and high-performance backend

Tech Stack
Frontend: React, Tailwind CSS, Socket.io-client
Backend: Spring Boot, WebSockets, MongoDB
Authentication: JWT-based authentication
Deployment: AWS
Setup Instructions
1️⃣ Clone the repository:

sh
Copy
Edit
git clone https://github.com/Prateek-2901/room-based-chatapp.git
cd room-based-chatapp
2️⃣ Backend Setup:

Configure MongoDB and update application.properties
Run the Spring Boot application
sh
Copy
Edit
mvn spring-boot:run
3️⃣ Frontend Setup:

Navigate to the frontend folder
Install dependencies and start the React app
sh
Copy
Edit
npm install  
npm start  
