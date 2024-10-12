# Task Manager App
This app is built using Node.js, Express, and MongoDB. The app focuses on basic CRUD operations for managing tasks. Users can create, read, update, and delete tasks.

## Features
- **Task CRUD Operations**: Users can create, read, update, and delete tasks.
- **Simple Interface**: The app provides a clean and intuitive interface for managing tasks.

## Technologies Used
- Node.js
- Express
- MongoDB

## Prerequisites
Make sure you have the following installed on your machine:
- Node.js
- npm
- MongoDB

## Getting Started
1. Clone the repository: `git clone https://github.com/himanshuV09/task-manager-app`
2. Navigate to the project directory: `cd task-manager-app`
3. Install dependencies: `npm install`
4. Set up your MongoDB database
5. Update the connection string in `config/db.js`
6. Start the application: `npm start`
7. Open your browser: Go to http://localhost:**** to access the Task Manager app.

## Project Structure
- **Controllers**: Contains logic for handling different HTTP requests related to tasks.
- **Models**: Includes MongoDB schema definition for tasks.
- **Routes**: Defines API routes for handling task-related operations.
- **Middleware**: Includes custom middleware functions like `asyncWrapper`, `notFound`, and `error-handler`.
- **Configuration**: Configuration files like `config/db.js` contain settings such as the MongoDB connection string.


