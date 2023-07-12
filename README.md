# MERN Authentication Project
![screenshot 2023-07-12 at 23 51 13](https://github.com/IvanKhutso/MERN-Authentication-JWT/assets/64652828/a374d46b-59b5-4986-bffc-e862f71fcce6)


This is a full-stack authentication project built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides a user registration and login system with token-based authentication.

## Features


https://github.com/IvanKhutso/MERN-Authentication-JWT/assets/64652828/e73ded96-2c55-415c-9af8-a0bb6e00f335


- User registration with input validation
- User login with token-based authentication
- Protected routes that require authentication
- Access control for different user roles (admin, regular user)
- User profile management
- Password hashing for secure storage
- Error handling and validation messages
- Responsive design using Bootstrap

## Prerequisites

Before running the project, make sure you have the following installed on your machine:

- Node.js (version 14 or higher)
- MongoDB (running locally or a cloud-based service)
- NPM or Yarn package manager

## Installation

1. Clone the repository: git clone https://github.com/IvanKhutso/MERN-Authentication-JWT.git 
2. Navigate to the project directory: cd MERN-Authentication-JWT 
3. Install the dependencies: npm install 
4. Create a `.env` file in the root directory with the following variables: MONGODB_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>


Replace `<your_mongodb_uri>` with the URI of your MongoDB database and `<your_jwt_secret>` with a secret key for JWT token generation.

5. Start the development server: npm run dev
This will concurrently run the backend and frontend servers.

6. Open your web browser and go to `http://localhost:8000` to view the application.

## Usage

- Register a new user by providing a valid email address and password.
- Log in using the registered email address and password.
- Access the protected routes, such as the user profile page, which require authentication.
- Log out to invalidate the token and remove the user session.

## Folder Structure

The project follows a standard MERN folder structure:

- `backend`: Contains the Node.js server code and API routes.
- `frontend`: Contains the React.js client code and UI components.
- `config`: Contains configuration files for the server, including the database connection and JWT secret.
- `models`: Defines the data models for MongoDB using Mongoose.
- `routes`: Contains the server-side API routes.
- `client`: Contains the React.js client code.
- `middleware`: Includes middleware functions for authentication and authorization.
- `controllers`: Contains the server-side logic for handling API requests.
- `validation`: Includes input validation logic using `express-validator`.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments



