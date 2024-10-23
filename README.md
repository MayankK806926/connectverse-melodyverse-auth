# connectverse-melodyverse-auth
# Login and Signup App - "MelodyVerse" & "Connectverse"

This project is a full-stack web application with a **Node.js + Express** backend and a **React.js** frontend, implementing **JWT-based authentication**. The backend API handles user registration and login, while the frontend provides responsive login and signup screens.

## Project Overview

This app consists of:

- **Connectverse**: A backend Node.js API that handles user authentication (signup and login).
- **MelodyVerse**: A frontend music streaming service with user registration and login screens built using React and styled with Tailwind CSS.

## Features

- **User Registration**: Allows users to create an account by providing a username, email, and password.
- **User Login**: Users can log in using their email and password. A JWT token is generated upon successful authentication.
- **JWT Authentication**: Ensures secure routes and protects user data.
- **Responsive Design**: Tailored for multiple devices (desktop, tablet, mobile) using **Tailwind CSS**.
- **React Router**: Handles page navigation between login, signup, and home.

## Technology Stack

### Backend:
- Node.js
- Express.js
- MongoDB (or any preferred database)
- JWT (jsonwebtoken) for authentication
- bcrypt.js for password hashing
- dotenv for environment variables

### Frontend:
- React.js
- Axios for HTTP requests
- React Router DOM for navigation
- Tailwind CSS for styling
