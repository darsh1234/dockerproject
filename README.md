# Docker Todo List Starter Project

This project is a simple Todo List application built to gain hands-on experience with Docker. It consists of a FastAPI backend, a MongoDB database, and a basic frontend, all containerized using Docker.

## Project Structure

- Backend: FastAPI application
- Frontend: Simple HTML interface
- Database: MongoDB
- Additional: Mongo Express for database management

## Technologies Used

- Python 3.12+
- FastAPI
- MongoDB
- Docker & Docker Compose
- HTML (for frontend)

## Features

- Create todo items
- List todo items
- Delete todo items
- Containerized application setup

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running the Application

1. Clone this repository
2. Navigate to the project directory
3. Create necessary `.env` files in the `backend/`, `mongodb/`, and `mongo-express/` directories
4. Run the following commands:

`docker compose build`

`docker compose up`

5. Access the application:
- Frontend: http://localhost:80
- Backend API: http://localhost:8000
- Mongo Express: http://localhost:8081

## Project Components

### Backend (FastAPI)

The backend is a Python application using FastAPI. It provides API endpoints for creating, reading, and deleting todo items.

### Frontend

A basic HTML interface for interacting with the Todo List.

### Database

MongoDB is used as the database to store todo items.

### Mongo Express

Included for easy database management and visualization.

## Configuration

The `docker-compose.yml` file defines the services and their configurations. Environment variables are managed through `.env` files for each service.

## Development

For development purposes, the project uses `pyproject.toml` for Python package management and `requirements.txt` for listing all Python dependencies.

## Learning Outcomes

This project serves as an introduction to:
- Containerizing applications with Docker
- Managing multi-container applications with Docker Compose
- Integrating different services (API, database, frontend) in a containerized environment
- Basic API development with FastAPI
- NoSQL database usage with MongoDB

## Next Steps

- Enhance the frontend with a JavaScript framework
- Add more CRUD operations
- Implement user authentication
- Expand test coverage

Feel free to fork this project and extend it as you continue learning about Docker and web development!
