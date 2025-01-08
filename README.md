# Library Management System

This project is a **MERN (MongoDB, Express, React, Node.js)**-based Library Management System designed to manage books, users, and transactions efficiently. It provides role-based access for admins and librarians, along with feedback and book request functionalities.

## Features

- **Admin Functionality**:
  - Manage users, books, and book requests.
  - View user history and feedback.
- **Librarian Functionality**:
  - Manage books and process book requests.
- **User Functionality**:
  - Browse books, request books, and provide feedback.
- **Authentication**:
  - Role-based access (Admin, Librarian, User).
  - JWT-based token authentication.
- **Password Recovery**:
  - Forgot password functionality with email reset.

## Demo

- **Backend**: Hosted on [Render](https://render.com/).
  
### Admin Login Credentials
- **Email**: `navneetkumar1705@gmail.com`
- **Password**: `123456`

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- Node.js
- MongoDB
- npm

### Clone the Repository
```bash
git clone https://github.com/navneetbind/Library_management_system.git
cd Library_management_system
```

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` directory with the following variables:
   ```env
   PORT=5000
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
   EMAIL_USERNAME=<your_email@example.com>
   EMAIL_PASSWORD=<your_email_password>
   ```
4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
   ```

### Accessing the Application
- Frontend: `http://localhost:5173`
- Backend: `http://localhost:5000`

## Usage

### Admin Panel
1. Log in using the admin credentials provided above.
2. Manage books, users, and requests from the admin dashboard.

### User Panel
1. Register and log in as a user.
2. Browse available books, request them, and leave feedback.

## Technologies Used

- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT
