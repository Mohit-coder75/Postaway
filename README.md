# Social Media Backend REST API(Postaway)

A robust backend REST API for a social media platform that allows users to post, comment, like, send friend requests, and reset their passwords using OTP (One-Time Password) for enhanced security.

## Goal

The goal of this project is to develop a comprehensive social media backend that offers a secure and scalable solution for managing user interactions, content creation, and authentication.

## Features

- **User Authentication**: Secure user registration and login using JWT (JSON Web Tokens).
- **Password Reset with OTP**: Users can reset their passwords securely using OTP sent via email.
- **Post Management**: Users can create, update, delete, and view posts.
- **Comment System**: Users can comment on posts and engage in discussions.
- **Like Functionality**: Users can like or unlike posts and comments.
- **Friend Requests**: Users can send, accept, or reject friend requests.
- **Real-time Notifications**: Users receive notifications for likes, comments, and friend request actions.

## Technologies Used

- **Node.js**: JavaScript runtime environment for building server-side applications.
- **Express.js**: Web framework for Node.js to handle routing and middleware.
- **MongoDB**: NoSQL database for storing user data, posts, comments, and likes.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **JWT**: For secure user authentication.
- **Nodemailer**: To send OTPs for password reset.
- **Socket.io**: For real-time notifications (optional feature).

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Mohit-coder75/Postaway.git
    cd social-media-backend
    ```

2. **Install Dependencies:**
    Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed, then run:
    ```bash
    npm install
    ```

3. **Configure Environment Variables:**
    Create a `.env` file in the root directory and add the following:

    ```plaintext
    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    SMTP_HOST=your_smtp_host
    SMTP_PORT=your_smtp_port
    SMTP_USER=your_smtp_user
    SMTP_PASS=your_smtp_password
    ```

4. **Run the Application:**
    ```bash
    npm start
    ```

    The server will start on `http://localhost:8000`.

