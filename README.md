# Todo Application

A full-stack Todo application built with React (TypeScript) and Node.js.

## Features

- Create, Read, Update, and Delete todos
- Mark todos as complete/incomplete
- Modern UI with Material-UI
- MongoDB database for persistence
- RESTful API backend

## Prerequisites

- Node.js (v14 or higher)
- MongoDB installed and running locally
- npm or yarn package manager

## Setup

1. Clone the repository
2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd client
   npm install
   ```

4. Create a `.env` file in the root directory with the following content:
   ```
   MONGODB_URI=mongodb://localhost:27017/todo-app
   PORT=5000
   ```

## Running the Application

1. Start the backend server:
   ```bash
   npm run server
   ```

2. In a new terminal, start the frontend development server:
   ```bash
   cd client
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## API Endpoints

- GET `/api/todos` - Get all todos
- POST `/api/todos` - Create a new todo
- PUT `/api/todos/:id` - Toggle todo completion status
- DELETE `/api/todos/:id` - Delete a todo

## Technologies Used

- Frontend:
  - React with TypeScript
  - Material-UI for styling
  - Axios for API calls

- Backend:
  - Node.js with Express
  - MongoDB with Mongoose
  - CORS for cross-origin requests
  - dotenv for environment variables 