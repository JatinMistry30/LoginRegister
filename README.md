
# LoginRegister - User Authentication System

## Overview
The **LoginRegister** project provides a full-stack authentication system using **React.js** for the frontend, **Node.js** for the backend, and **MySQL** for database management. This system allows users to register, log in, and log out securely.

## Features
- **User Registration**: Secure user sign-up with validation.
- **User Login**: Authentication with email and password.
- **User Logout**: Allows users to securely log out of the system.

## Technologies
- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MySQL

## Installation

### Prerequisites
- **Node.js** (>= 14.x)
- **MySQL** (for database)

### Frontend Setup:
1. Navigate to the `frontend/` directory:
   ```bash
   cd frontend
   ```
2. Install frontend dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```

### Backend Setup:
1. Navigate to the `backend/` directory:
   ```bash
   cd backend
   ```
2. Install backend dependencies:
   ```bash
   npm install
   ```
3. Configure the database connection in the backend (`config.js` or `.env` file).
4. Run the backend server:
   ```bash
   node server.js
   ```

## Database Setup:
1. Install MySQL and create a new database.
2. Configure the database connection in the backend by editing the connection settings (`config.js`).
3. Run the provided SQL commands to create necessary tables for user authentication.

## Usage
- **Register**: Users can sign up by providing a username, email, and password.
- **Login**: Registered users can log in using their credentials.
- **Logout**: Logged-in users can securely log out of the system.

## Notes
- Ensure both the frontend and backend servers are running simultaneously.
- The frontend communicates with the backend for user authentication and session management.

## License
This project is open-source and available for contributions. Feel free to fork, modify, and submit pull requests.
