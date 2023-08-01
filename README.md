# Naxel
# E-Commerce Website


This is an E-Commerce website built collaboratively with my friends. The project features authentication, authorization, JWT token generation, protected routes, and MongoDB as the database. It is developed using Vite-React with JSX syntax for enhanced performance. The application is styled using Tailwind CSS, and global state management is achieved through React Redux.

## Features

- User Authentication: Users can sign up, log in, and log out securely using JWT-based authentication.
- Authorization: Different levels of access are provided to users based on their roles and permissions.
- JWT Token Generation: JWT tokens are generated for secure authentication and authorization.
- Protected Routes: Certain routes are protected and accessible only to authenticated users.
- MongoDB Database: MongoDB is used as the database to store and manage the application data.
- Vite-React with JSX: The project utilizes Vite-React for faster development and improved performance with JSX syntax.
- Tailwind CSS Styling: Tailwind CSS is used to create a visually appealing and responsive user interface.
- React Redux State Management: Global state management is implemented using React Redux for better scalability and organization.

## Technologies Used

- Vite-React (with JSX)
- React Redux (React Redux Toolkit)
- MongoDB
- Tailwind CSS
- Yarn Package Manager

## prerequisites
- Node.js: Make sure you have Node.js installed on your local machine. You can download and install it from the official Node.js website: https://nodejs.org.
- Yarn Package Manager: Install Yarn on your machine, as it will be used to manage the project's dependencies. You can find installation instructions for your specific operating system here: https://classic.yarnpkg.com/en/docs/install.
- MongoDB: Since the project uses MongoDB as the database, you'll need to have MongoDB installed and running on your local machine. You can download and install MongoDB Community Edition from the official website: https://www.mongodb.com/try/download/community.

 
## Getting Started

To run the project locally, follow these steps:

- 1. **Clone the repository:**
- git clone https://github.com/_____________/_____________git
- 2  **Navigate to the project directory.**
- cd ___________________________; cd frontend
- 3 **Install dependencies**
- yarn install
- 4 **Start the development server**
- yarn dev

Nilex/
  ├── frontend/
  │   ├── public/
  │   ├── src/
  │   │   ├── app/
  │   │   ├── components/
  │   │   ├── features/
  │   │   ├── App.jsx
  │   │   ├── index.jsx
  │   │   └── ...
  │   ├── package.json
  │   ├── .gitignore
  │   └── vite.config.js
  │   ├── tailwind.config.js
  │   ├── yarn.lock
  │   ├── Dockerfile.dev
  │   ├── ...
  |
  ├── api/
  │   ├── config/
  │   ├── controllers/
  │   ├── middlewares/
  │   ├── models/
  │   ├── routes/
  │   ├── index.js
  │   ├── package.json
  │   ├── .env
  │   ├── .gitignore
  │   ├── .Dockerfile.dev
  │   ├── ...
  |
  ├── docker-compose.yaml
  ├── package.json
  ├── .gitignore
  ├── ...

