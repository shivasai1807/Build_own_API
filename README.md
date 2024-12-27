# Build Your Own API

This project demonstrates how to build a simple API using JavaScript and Node.js. The API is designed to manage tasks, allowing users to create, read, update, and delete task records. It is an ideal starter project for learning about server-side programming and APIs.

## Project Structure

The project consists of the following files and folder paths:

- **models/Task.js**: Defines the structure and behavior of the `Task` model.
- **config/database.js**: Handles the database connection and operations.
- **public/index.html**: Provides a basic frontend interface to interact with the API.
- **package-lock.json**: Tracks the exact version of the dependencies.
- **package.json**: Lists the project dependencies and metadata.
- **server/server.js**: Contains the server logic and API endpoints.
- **controllers/tasks.js**: Manages task-related logic and operations.

## Features

- Create tasks
- Retrieve tasks
- Update tasks
- Delete tasks

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd build-own-api
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

## Running the Project

1. Start the server:
   ```bash
   node server/server.js
   ```

2. Open `public/index.html` in your browser to access the frontend interface.

3. Use tools like Postman or cURL to interact with the API endpoints directly.

## API Endpoints

### Base URL
```
http://localhost:3000
```

### Endpoints

- **GET /tasks**: Retrieve all tasks.
- **GET /tasks/:id**: Retrieve a task by ID.
- **POST /tasks**: Create a new task.
  - Body: `{ "title": "Task title", "description": "Task description" }`
- **PUT /tasks/:id**: Update an existing task.
  - Body: `{ "title": "Updated title", "description": "Updated description" }`
- **DELETE /tasks/:id**: Delete a task by ID.

## Dependencies

The project uses the following npm packages:

- Express: Web framework for Node.js.
- Body-parser: Middleware to parse request bodies.
- (Optional) A database library such as `mongoose` for MongoDB or `sqlite3`.

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License.

---

Happy coding!
