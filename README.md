# Web Application with Docker Compose

This project demonstrates containerizing a web application with Docker Compose. It consists of a frontend, backend, and MongoDB database, each running in its own container.

## Features

- Frontend: Single-page application with a form to submit name and email.
- Backend: Flask endpoint to store submitted data in MongoDB.
- Database: MongoDB to store user data.

## Prerequisites

Make sure you have the following installed on your system:

- Docker
- Docker Compose

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/webapp-docker-compose.git
    cd webapp-docker-compose
    ```

2. Build and run the Docker containers:

    ```bash
    docker-compose up --build
    ```

3. Access the web application in your browser at `http://localhost:8081`.

## Usage

- Access the frontend application at `http://localhos:8081`.
- Submit your name and email through the form.
- Submitted data will be stored in the MongoDB database via the Flask backend.
