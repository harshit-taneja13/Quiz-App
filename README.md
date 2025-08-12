# Quiz Application

## Project Overview
The Quiz Application is a web-based platform that allows users to take quizzes on various topics. It features a responsive design and provides an engaging user experience.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js
- **Microservices:** Go
- **Database:** MongoDB

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/harshit-taneja13/Quiz-App.git
   cd Quiz-App
   ```

2. **Install Dependencies**
   - For the frontend:
     ```bash
     cd client
     npm install
     ```
   - For the backend:
     ```bash
     cd server
     npm install
     ```

3. **Run the Application**
   - Start the backend server:
     ```bash
     cd server
     node index.js
     ```
   - Start the frontend application:
     ```bash
     cd client
     npm start
     ```

## Security Features
- **Authentication:** JWT-based authentication for secure user access.
- **Data Validation:** Input validation to protect against SQL injection and other attacks.
- **HTTPS:** Encrypted communication between the client and server.

## Folder Structure
```
Quiz-App/
├── client/            # Frontend application
│   ├── src/          # Source files for React
│   ├── public/       # Static files
│   └── package.json   # Frontend dependencies
├── server/            # Backend application
│   ├── routes/       # API routes
│   ├── models/       # Database models
│   └── index.js      # Entry point for the server
└── README.md          # Project documentation
```