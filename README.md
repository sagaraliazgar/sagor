# Simple Node.js Project

A boilerplate for a simple Node.js application using Express and Dotenv.

## Features

- **Express**: Fast, unopinionated, minimalist web framework.
- **Dotenv**: Loads environment variables from a `.env` file.
- **Nodemon**: Automatically restarts the server during development.

## Getting Started

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone the repository or download the source code.
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

- **Development Mode**:
  ```bash
  npm run dev
  ```
  The server will start at `http://localhost:3000` and restart on any file changes.

- **Production Mode**:
  ```bash
  npm start
  ```

## API Endpoints

- `GET /`: Returns a welcome message.
- `GET /health`: Returns the health status of the API.
