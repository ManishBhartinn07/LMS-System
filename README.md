# Learning Management System (LMS)

A full-stack Learning Management System with role-based authentication for Students, Teachers, and Administrators.

## Features
- Role-based authentication (Student, Teacher, Admin)
- Secure login system
- Dashboard for each user role
- MongoDB database integration
- JWT-based authentication

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd LMS2
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Install Frontend Dependencies
```bash
cd ../frontend
npm install
```

4. Create a .env file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

5. Start the Backend Server
```bash
cd backend
npm start
```

6. Start the Frontend Development Server
```bash
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

## Default Admin Credentials
- Email: admin@example.com
- Password: admin123

## Project Structure
```
LMS2/
├── frontend/          # React frontend application
├── backend/           # Node.js backend application
└── README.md         # Project documentation
``` # LMS-System
