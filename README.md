# Real-Time Chat Application

A real-time chat application built with a Next.js frontend and an Express.js backend powered by TypeScript. It features real-time messaging using Socket.IO, robust database management with Prisma, and efficient message handling with Kafka and Redis.

## Features

- Real-time messaging and live updates via Socket.IO.
- User authentication with JWT and password encryption using bcrypt.
- Prisma ORM for database operations.
- Kafka for message queuing.
- Redis and Upstash Kafka for caching and low-latency message streaming.
- Streamlined development with TypeScript, concurrently, and nodemon for automatic reloading.

## Tech Stack

- **Frontend:** Next.js, React.js
- **Backend:** Express.js, TypeScript
- **Database:** Prisma, PostgreSQL (or any supported by Prisma)
- **Messaging:** Kafka, Socket.IO
- **Caching:** Redis, Upstash Kafka
- **Authentication:** JWT, bcrypt
- **Development Tools:** Nodemon, Concurrently

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Aditya-040/Zephyr.git
    cd Zephyr
    ```

2. Install dependencies for both frontend and backend:

   **Frontend (Next.js):**

    ```bash
    cd frontend
    npm install
    ```

   **Backend (Express.js):**

    ```bash
    cd backend
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the root of the backend with the following variables:

    ```bash
    DATABASE_URL=<Your Prisma-supported database URL>
    JWT_SECRET=<Your JWT secret key>
    KAFKA_BROKER_URL=<Your Kafka broker URL>
    REDIS_URL=<Your Redis URL>
    ```

4. Run Prisma migrations:

    ```bash
    cd backend
    npx prisma migrate dev
    ```

## Usage

1. Start the frontend (Next.js):

    ```bash
    cd frontend
    npm run dev
    ```

2. Start the backend (Express.js):

    ```bash
    cd backend
    npm run dev
    ```

3. Open the app in your browser:

    ```bash
    http://localhost:3000
    ```

## Development

- **Frontend:** Run the Next.js development server for live reloading.

    ```bash
    npm run dev
    ```

- **Backend:** Start the Express server with automatic reloading using `concurrently` and `nodemon`.

    ```bash
    npm run dev
    ```

