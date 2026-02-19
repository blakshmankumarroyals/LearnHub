# LearnHub - Online Learning Platform

A comprehensive Online Learning Platform built with the MERN stack (MongoDB, Express, React, Node.js).

## Project Structure

- **client/**: React Frontend (Vite + Material UI)
- **server/**: Express Backend (Node.js + MongoDB)

## Pre-requisites

Here are the key prerequisites for developing this full-stack application using Node.js, Express.js, MongoDB, React.js:

### 1. Node.js and npm
Node.js is a powerful JavaScript runtime environment that allows you to run JavaScript code on the server-side.
- **Download**: [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
- **Installation**: [https://nodejs.org/en/download/package-manager/](https://nodejs.org/en/download/package-manager/)

### 2. MongoDB
MongoDB is a flexible and scalable NoSQL database.
- **Download**: [https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)
- **Installation**: [https://docs.mongodb.com/manual/installation/](https://docs.mongodb.com/manual/installation/)

### 3. Vite (Frontend Tool)
Vite is used for the frontend build and development server.
- Command to create (already done): `npm create vite@latest`

### 4. Express.js (Backend Framework)
Fast and minimalist web application framework for Node.js.
- Installation: `npm install express` (included in dependencies)

### 5. React.js (Frontend Library)
JavaScript library for building user interfaces.

---

## Installation & Setup

Follow these steps to get the project running:

1.  **Navigate to the project directory**:
    ```bash
    cd LearnHub
    ```

2.  **Install Backend Dependencies**:
    ```bash
    cd backend
    npm install
    ```
    *Ensure you have a `.env` file in `backend/` with `MONGO_URI` and `JWT_SECRET`.*

3.  **Install Frontend Dependencies**:
    ```bash
    cd ../frontend
    npm install
    ```

4.  **Start the Development Servers**:

    - **Backend**:
      ```bash
      cd backend
      npm run dev
      ```
      *Server runs on port 5000.*

    - **Frontend**:
      ```bash
      cd frontend
      npm run dev
      ```
      *The App will be accessible at http://localhost:5173* (or as specified in terminal).

## Database Connectivity
Use Mongoose to connect your Node.js server with the MongoDB database.
Reference: [Node.js Mongoose MongoDB](https://www.section.io/engineering-education/nodejs-mongoosejs-mongodb/)

## Technologies Used
- **Frontend**: React.js, Vite, Material UI (for premium UI/UX).
- **Backend**: Node.js, Express.js.
- **Database**: MongoDB.


## Features
- **User Authentication**: Login and Register for Students.
- **Course Catalog**: Browse available courses with filtering (mocked in frontend).
- **Course Detail**: View detailed course information and syllabus.
- **Student Dashboard**: Track enrolled courses and progress.
- **Responsive Design**: Built with Material UI for a premium experience on all devices.

## Note on Environment
If you encounter `npm` errors during installation, please ensure your Node.js and npm installation is healthy.
