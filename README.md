# Keeper - Note Taking Application

Keeper is a note-taking application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This application allows users to create, edit, delete, and organize their notes efficiently.

## Features

- **Create and View Notes:** Users can create new notes, view existing notes, and categorize them for easy access.
- **Edit and Delete:** Edit note contents and delete notes when necessary.
- **User Authentication:** Secure user authentication and authorization functionalities for note management.
- **Responsive Design:** The application is designed to work seamlessly on various devices.

## Technologies Used

- **MongoDB:** NoSQL database used for storing note data.
- **Express.js:** Backend framework for handling HTTP requests and routing.
- **React.js:** Frontend library for building user interfaces.
- **Node.js:** JavaScript runtime environment for running the server-side code.
- **Mongoose:** MongoDB object modeling for Node.js.
- **JWT Authentication:** JSON Web Token-based authentication for user security.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed or access to a MongoDB instance

### Installation

1. Clone the repository: `git clone https://github.com/your-username/keeper-app.git`
2. Navigate to the project directory: `cd keeper-app`
3. Install dependencies for both backend and frontend:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the `backend` directory following the `.env.example` file and add your MongoDB connection string.
5. Start the application:
   ```bash
   # Run backend server (from the backend directory)
   npm start

   # Run frontend (from the frontend directory)
   npm start
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any suggested enhancements or bug fixes.

