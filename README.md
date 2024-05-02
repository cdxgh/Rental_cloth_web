# Rental Cloth Website

This is a web application for renting clothes, built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with TypeScript and Vite as the build tool.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Browse and search for available clothes
- Rent clothes for a specified duration
- View rental history and current rentals
- Admin dashboard for managing clothes, users, and rentals

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your local machine
- MongoDB Atlas account (or local MongoDB server) for database storage

## Getting Started

To get a local copy up and running, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/rental-cloth-website.git
   Navigate to the project directory:

bash

cd rental-cloth-website

Install dependencies:

bash

npm install

Set up environment variables:

    Create a .env file in the root directory

    Add the following environment variables:

    plaintext

    PORT=3000
    MONGODB_URI=your-mongodb-uri
    JWT_SECRET=your-jwt-secret

Start the development server:

bash

    npm run dev

    Open your browser and visit http://localhost:3000 to view the website.

Folder Structure

The project structure follows the conventions of a MERN stack application with TypeScript:

php

rental-cloth-website/
│
├── client/             # Frontend (React.js) code
│   ├── public/         # Static assets
│   └── src/            # React components and TypeScript files
│
├── server/             # Backend (Express.js) code
│   ├── controllers/    # Route controllers
│   ├── models/         # Mongoose models
│   ├── routes/         # Express routes
│   └── utils/          # Utility functions
│
└── package.json        # Project dependencies and scripts

Technologies Used

    MongoDB: NoSQL database for storing user, cloth, and rental data
    Express.js: Web framework for building RESTful APIs
    React.js: Frontend library for building user interfaces
    Node.js: JavaScript runtime environment for backend development
    TypeScript: Superset of JavaScript for static typing
    Vite: Frontend build tool for modern web development

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.
