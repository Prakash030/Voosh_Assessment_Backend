# Task Management API

The Task Management API is a Node.js application that provides CRUD (Create, Read, Update, Delete) functionalities for managing tasks and user management features. Built with Express and MongoDB, this API allows users to create tasks, update their details, retrieve tasks for a specific user, and delete tasks. It also supports user registration and login, including Google authentication.

## Features

### Task Management
- **Create a Task**: Add a new task with details such as title, description, and status.
- **Get Tasks**: Retrieve tasks for a specific user.
- **Update a Task**: Modify the title, description, or status of an existing task.
- **Delete a Task**: Remove a specific task.
- **Delete All Tasks**: Remove all tasks for a user.

### User Management
- **Register a User**: Create a new user account.
- **Login**: Authenticate users with email and password.
- **Google Authentication**: Sign in using Google.

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository

2. **Install dependencies:**

    ```bash
    npm install

3. **Configure environment variables:**

    ```bash
    MONGODB_URI=mongodb://localhost:27017/taskdb
    PORT=3000
    GOOGLE_CLIENT_ID=your-google-client-id
    GOOGLE_CLIENT_SECRET=your-google-client-secret
    SESSION_SECRET=your-session-secret

4. **Running the Application**

    ```bash
    npm start

5. **Unit test**

    ```bash
    npm test



