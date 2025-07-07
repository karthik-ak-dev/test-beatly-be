# test-beatly-be

A simple Node.js application with Express that responds with 'Hello, World!' and provides a health check route.

## Running Locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Visit [http://localhost:3000](http://localhost:3000) to see 'Hello, World!'.
4. Health check: [http://localhost:3000/health](http://localhost:3000/health) returns `{ "status": "ok" }`.

## Running with Docker

1. Build the Docker image:
   ```bash
   docker build -t test-beatly-be .
   ```
2. Run the container:
   ```bash
   docker run -p 3000:3000 test-beatly-be
   ```
3. Access the app and health check as above.
