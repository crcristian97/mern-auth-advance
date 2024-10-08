# Email Verification App

This is an email verification app built using Node.js, MongoDB, and React with Vite. It allows users to register and verify their email addresses through a token-based system. The app uses Mailtrap to handle email verification in development.

## Features

- User registration with email verification
- Secure password hashing using `bcryptjs`
- JWT-based authentication for users
- MongoDB as the database to store user information
- Express.js as the backend framework
- Frontend built with React and Vite
- CORS support for secure cross-origin requests
- Environment variables management with `dotenv`
- Mailtrap integration for email sending during development

## Tech Stack

### Backend
- **Node.js**: JavaScript runtime for server-side development.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing user data.
- **Mongoose**: ODM for MongoDB, used to define schemas and interact with the database.
- **jsonwebtoken**: For token-based authentication.
- **bcryptjs**: For secure password hashing.
- **Mailtrap**: Email testing service used to send verification emails.
- **dotenv**: To manage environment variables.
- **Nodemon**: Development tool to automatically restart the server on file changes.

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Vite**: A fast build tool for modern web development.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Node.js (v14.x or later)
- MongoDB (local or hosted database)
- Mailtrap account for email testing

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/email-verification-app.git
   cd email-verification-app
